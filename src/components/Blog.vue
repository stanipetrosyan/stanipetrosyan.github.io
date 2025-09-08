<script setup>
import {
  FwbCard,
  FwbImg,
  FwbButton
} from 'flowbite-vue'

const imgUrl = new URL('../assets/myself.jpg', import.meta.url).href

const posts = [
  {
    title: "How to implement SAGA pattern in Go",
    img: "https://flowbite.com/docs/images/blog/image-1.jpg",
    link: "",
    author: "Stanislav",
    date: "Coming soon"
  },
  {
    title: "How to implement CQRS and Event Sourcing pattern in Go",
    img: "https://flowbite.com/docs/images/blog/image-1.jpg",
    link: "https://medium.com/@stani.petrosyan/how-to-implement-cqrs-and-event-sourcing-pattern-in-go-fd47dc0afd80",
    author: "Stanislav",
    date: "Jun 10, 2024 ⋅ 7 min read"
  },
  {
    title: " Vert.x Circuit Breaker",
    img: "https://flowbite.com/docs/images/blog/image-1.jpg",
    link: "https://dev.to/cherrychain/vert-x-circuit-breaker-pattern-19pe",
    author: "Stanislav",
    date: "May 28, 2021 ⋅ 5 min read"
  }
]

</script>

<template>
  <div class="grid grid-cols-9 gap-4 mt-12">
    <div class="col-span-3 row-span-2" v-for="post in posts">
      <fwb-card variant="horizontal" class="text-center p-10 bg-gray-900 dark:bg-teal-600">
        <fwb-img alt="flowbite-vue"
          img-class="rounded-lg transition-all duration-300 cursor-pointer filter grayscale hover:grayscale-0"
          size="max-w-sm" :src=post.img>
        </fwb-img>


        <div class="p-5">
          <h5 class="mb-2 text-2xl font-bold tracking-tight text-white">{{  post.title }}</h5>
          <p class="font-normal text-gray-700 dark:text-gray-400">
          </p>
        </div>

        <div class="flex items-start">
          <div class="w-14">
            <img class="w-8 h-8 rounded-full" :src=imgUrl alt="Neil image">
          </div>
          <div class="flex-1">
            <p class="text-sm font-medium dark:text-white">
              {{ post.author }}
            </p>
            <p class="text-sm text-gray-400 dark:text-gray-300">
              {{  post.date }}
            </p>
          </div>
          <div class="flex-1">
            <fwb-button
              :href=post.link
              class="dark:bg-gray-900 bg-teal-600">
              Explore
            </fwb-button>
          </div>
        </div>
      </fwb-card>
    </div>
  </div>

</template>
