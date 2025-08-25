<script setup>
import {
  FwbCard,
  FwbImg,
  FwbButton
} from 'flowbite-vue'

const imgUrl = new URL('../assets/myself.jpg', import.meta.url).href


</script>

<template>
  <div class="grid grid-cols-4 gap-4 mt-12">
    <div class="col-start-2 col-end-4">

      <fwb-card variant="horizontal" class="text-center p-10 bg-gray-900 dark:bg-teal-600">
        <fwb-img alt="flowbite-vue"
          img-class="rounded-lg transition-all duration-300 cursor-pointer filter grayscale hover:grayscale-0"
          size="max-w-lg" src="https://flowbite.com/docs/images/blog/image-1.jpg">
        </fwb-img>


        <div class="p-5">
          <h5 class="mb-2 text-2xl font-bold tracking-tight text-white">
            How to implement CQRS and Event Sourcing pattern in Go
          </h5>
          <p class="font-normal text-gray-700 dark:text-gray-400">
            I decided to write this article with the idea to show how it is possible to achieve a pattern to help us
            write projects with more logic business in Golang.
          </p>
        </div>

        <div class="flex items-start">
          <div class="w-14">
            <img class="w-8 h-8 rounded-full" :src=imgUrl alt="Neil image">
          </div>
          <div class="flex-1">
            <p class="text-sm font-medium dark:text-white">
              Stanislav
            </p>
            <p class="text-sm text-gray-500 dark:text-gray-400">
              Aug 25, 2025 ⋅ 8 min read
            </p>


          </div>
          <div class="flex-1">
            <fwb-button
              href="https://medium.com/@stani.petrosyan/how-to-implement-cqrs-and-event-sourcing-pattern-in-go-fd47dc0afd80"
              class="dark:bg-gray-900 bg-teal-600">
              Explore
            </fwb-button>
          </div>
        </div>
      </fwb-card>

    </div>
  </div>




</template>
