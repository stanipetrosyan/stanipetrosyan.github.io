<script setup>
import { RouterLink, RouterView } from 'vue-router'
import { FwbButton, FwbBreadcrumb, FwbBreadcrumbItem } from 'flowbite-vue';
import { onMounted } from 'vue';

onMounted(() => {
  var themeToggleBtn = document.getElementById('theme-toggle');

  themeToggleBtn.addEventListener('click', function() {

    if (localStorage.getItem('color-theme')) {
      if (localStorage.getItem('color-theme') === 'light') {
        document.documentElement.classList.add('dark');
        localStorage.setItem('color-theme', 'dark');
      } else {
        document.documentElement.classList.remove('dark');
        localStorage.setItem('color-theme', 'light');
      }

      // if NOT set via local storage previously
    } else {
      if (document.documentElement.classList.contains('dark')) {
        document.documentElement.classList.remove('dark');
        localStorage.setItem('color-theme', 'light');
      } else {
        document.documentElement.classList.add('dark');
        localStorage.setItem('color-theme', 'dark');
      }
    }
  })
})

</script>

<template>
  <div class="flex flex-row m-8">
    <!--<div class="flex justify-end">
      <fwb-button id="theme-toggle">Dark</fwb-button>
    </div>-->
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
