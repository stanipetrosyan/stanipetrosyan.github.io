<script setup>
import { ref } from 'vue'
import { FwbTab, FwbTabs } from 'flowbite-vue'
import Experience from '@/components/Experience.vue';

const activeTab = ref('first')
</script>

<template>
   <fwb-tabs v-model="activeTab" variant="pills" class="p-5">
    <fwb-tab name="experience" title="Experience" >
      <Experience></Experience>
    </fwb-tab>
    <fwb-tab name="second" title="Second">
      Lorem ipsum dolor...
    </fwb-tab>
    <fwb-tab name="third" title="Third">
      Lorem ipsum dolor...
    </fwb-tab>
    <fwb-tab name="fourth" title="Fourth" disabled>
      Lorem ipsum dolor...
    </fwb-tab>
  </fwb-tabs>
</template>

<style>
</style>
