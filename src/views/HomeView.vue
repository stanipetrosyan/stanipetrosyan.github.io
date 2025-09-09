<script setup>
import { FwbImg, FwbHeading, FwbCard, FwbFooter, FwbButton } from 'flowbite-vue'


const imgUrl = new URL('../assets/myself.jpg', import.meta.url).href

</script>

<template>
  <main>
    <span class="mt-10">
      <div class="rounded-lg p-8 md:p-12 mb-8">
        <fwb-img :src=imgUrl class="h-64 w-64 rounded-full mx-auto mb-8" />
      </div>

      <div class="py-8 px-4 mx-auto max-w-screen-xl lg:py-16">
        <div class="grid md:grid-cols-2 gap-8">
          <div class="bg-gray-900 dark:bg-teal-600 rounded-lg p-8 md:p-12">
            <h2 class="mb-2 text-3xl font-extrabold tracking-tight text-white">
              Full Stack Developer
            </h2>
            <p class="text-lg font-normal text-gray-400 dark:text-gray-200 mb-4"> Passionate about computer science,
              with a
              strong interest in
              high-quality software development. I pay particular attention to
              writing clean, readable, and maintainable code. I see myself as a Full
              Stack Developer, as I have learned techniques that cover the entire
              project development lifecycle.</p>
            <a href="#/software"
              class="text-blue-600 dark:text-blue-500 hover:underline font-medium text-lg inline-flex items-center">Read
              more
              <svg class="w-3.5 h-3.5 ms-2 rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg"
                fill="none" viewBox="0 0 14 10">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                  d="M1 5h12m0 0L9 1m4 4L9 9" />
              </svg>
            </a>
          </div>
          <div class="bg-gray-900 dark:bg-teal-600 rounded-lg p-8 md:p-12">
            <h2 class="mb-2 text-3xl font-extrabold tracking-tight text-white">
              Game Developer
            </h2>
            <p class="text-lg font-normal text-gray-400 dark:text-gray-200 mb-4"> I have a strong passion for video game
              development. I'm fascinated by
              every aspect of the process, from designing a story or gameplay
              mechanic to bringing it to life. I enjoy creating environments,
              developing user interfaces, and programming the interactive dynamics
              that make each game unique. I’m currently studying the Unity3D engine
              and enjoy creating Pixel Art in my free time.</p>
            <a href="#/game"
              class="text-blue-600 dark:text-blue-500 hover:underline font-medium text-lg inline-flex items-center">Read
              more
              <svg class="w-3.5 h-3.5 ms-2 rtl:rotate-180" aria-hidden="true" xmlns="http://www.w3.org/2000/svg"
                fill="none" viewBox="0 0 14 10">
                <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2"
                  d="M1 5h12m0 0L9 1m4 4L9 9" />
              </svg>
            </a>
          </div>
        </div>
      </div>
    </span>

  </main>







</template>
