<script setup>
import { RouterLink, RouterView } from 'vue-router'
import { FwbButton, FwbBreadcrumb, FwbBreadcrumbItem } from 'flowbite-vue';
import DarkMode from './components/DarkMode.vue';


</script>

<template>
  <div class="flex flex-row m-8">
    <div class="flex justify-end">
      <DarkMode></DarkMode>
    </div>
    <div class="place-self-start">
      <fwb-breadcrumb>
        <fwb-breadcrumb-item home href="/">
          Home
        </fwb-breadcrumb-item>
      </fwb-breadcrumb>
    </div>



  </div>

  <RouterView />
</template>

<style scoped></style>
