<script setup>
import { RouterLink, RouterView } from 'vue-router'
import { FwbButton, FwbBreadcrumb, FwbBreadcrumbItem } from 'flowbite-vue';
import DarkMode from './components/DarkMode.vue';


</script>

<template>

  <div class="flex justify-end m-6">
    <DarkMode></DarkMode>
  </div>
  <div class="flex flex-row m-6">
    <div class="place-self-center">
      <fwb-breadcrumb>
        <fwb-breadcrumb-item  home href="/">
          Home
        </fwb-breadcrumb-item>
      </fwb-breadcrumb>
    </div>
  </div>


  <RouterView />
</template>

<style>

  a {
    color: white !important;
  }
</style>
