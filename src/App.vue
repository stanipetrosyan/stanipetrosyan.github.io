<script setup>
import { RouterLink, RouterView } from 'vue-router'
import { FwbButton, FwbBreadcrumb, FwbBreadcrumbItem } from 'flowbite-vue';
</script>

<template>
  <header>
    <fwb-breadcrumb solid>
      <fwb-breadcrumb-item home href="/home">
        Home
      </fwb-breadcrumb-item>
      <fwb-breadcrumb-item href="/software">
        Projects
      </fwb-breadcrumb-item>
      <fwb-breadcrumb-item>
        Flowbite
      </fwb-breadcrumb-item>
    </fwb-breadcrumb>
  </header>

  <RouterView />
</template>

<style scoped>
</style>
