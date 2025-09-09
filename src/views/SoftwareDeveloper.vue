<script setup>
import { ref } from 'vue'
import Experience from '@/components/Experience.vue';
import Knowledge from '@/components/Knowledge.vue';
import Blog from '@/components/Blog.vue';
import Projects from '@/components/Projects.vue';

const currentTab = ref('Experience')

const tabs = {
  Experience,
  Knowledge,
  Projects,
  Blog
}

</script>

<template>
  <aside id="default-sidebar" class="fixed z-40 w-64 h-screen transition-transform -translate-x-full sm:translate-x-0"
    aria-label="Sidebar">

    <div class="h-full px-3 py-4 overflow-y-auto bg-teal-600 dark:bg-gray-900"> 
      <ul v-for="(_, tab) in tabs" class="space-y-2 font-medium">
        <li class="mt-2">
          <div @click="currentTab = tab" :class="{ 'dark:bg-teal-600 bg-gray-900': currentTab === tab }"
            class="flex items-center p-2 rounded-lg text-white hover:bg-gray-900 dark:hover:bg-teal-600">
            <span class="ms-3"> {{ tab }}</span>
          </div>
        </li>
      </ul>
    </div>
  </aside>

  <div class="p-4 sm:ml-64">
    <div class="p-4 border-2 border-gray-200 border-dashed rounded-lg dark:border-gray-700">
      <component :is="tabs[currentTab]"></component>
    </div>
  </div>

</template>

<style scoped>
</style>
