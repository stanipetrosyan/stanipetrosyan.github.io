<script setup>
import { FwbImg, FwbHeading, FwbCard, FwbFooter, FwbButton } from 'flowbite-vue'


const imgUrl = new URL('../assets/myself.jpg', import.meta.url).href

</script>

<template>
  <main>
    <span class="mt-10">
      <div class="grid grid-cols-8 grid-rows-2 gap-4 mt-10">
        <div class="col-start-4 col-end-6 row-start-1 row-end-2 mb-10">
          <fwb-img :src=imgUrl class="h-64 w-64 rounded-full mx-auto mb-8" />

          <fwb-heading tag="h5">I have been passionate about computer science since my early high
            school years. I like to challenge myself with problems and dedicate
            myself fully to solving them.</fwb-heading>
        </div>

        <div class="col-start-2 col-end-5 row-start-2 row-end-3 justify-self-center">
          <fwb-card class="sm:p-10 md:p-12 p-12 w-xl bg-gray-900 dark:bg-teal-600" variant="horizontal">
            <a href="#/software">
              <h5 class="mb-2 text-2xl font-semibold tracking-tight text-white">
                Full Stack Developer
              </h5>
            </a>
            <p class="mb-3 font-normal text-gray-400 dark:text-gray-200">
              Passionate about computer science, with a strong interest in
              high-quality software development. I pay particular attention to
              writing clean, readable, and maintainable code. I see myself as a Full
              Stack Developer, as I have learned techniques that cover the entire
              project development lifecycle.
            </p>
             <fwb-button href="#/software" class="dark:bg-gray-900 bg-teal-600">
              Explore
            </fwb-button>

          </fwb-card>
        </div>
        <div class="col-start-5 col-end-8 row-start-2 justify-self-center">
          <fwb-card class="sm:p-10 md:p-12 p-12 w-full bg-gray-900 dark:bg-teal-600" variant="horizontal">
            <a href="#/game">
              <h5 class="mb-2 text-2xl font-semibold tracking-tight text-white">
                Game Developer
              </h5>
            </a>
            <p class="mb-3 font-normal text-gray-400 dark:text-gray-200">
              I have a strong passion for video game development. I'm fascinated by
              every aspect of the process, from designing a story or gameplay
              mechanic to bringing it to life. I enjoy creating environments,
              developing user interfaces, and programming the interactive dynamics
              that make each game unique. I’m currently studying the Unity3D engine
              and enjoy creating Pixel Art in my free time.
            </p>
            <fwb-button href="#/game" class="dark:bg-gray-900 bg-teal-600">
              Explore
            </fwb-button>
          </fwb-card>
        </div>
        <div class="col-start-2 col-end-8 row-start-4 row-end-5 mb-10">
          <fwb-footer class="bg-gray-900 dark:bg-teal-600">
              <h5 class="mb-2 text-3xl font-bold text-white">About me</h5>
          </fwb-footer>
        </div>
      </div>
    </span>
  </main>
</template>
