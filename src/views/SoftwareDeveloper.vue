<script setup>
import { ref } from 'vue'
import { FwbTab, FwbTabs } from 'flowbite-vue'
import Experience from '@/components/Experience.vue';
import Knowledge from '@/components/Knowledge.vue';

const activeTab = ref('first')
</script>

<template>
  <fwb-tabs v-model="activeTab" variant="underline" class="p-5 dark">
    <fwb-tab name="experience" title="Experience" >
      <Experience></Experience>
    </fwb-tab>
    <fwb-tab name="knowledge" title="Knowledge">
      <Knowledge></Knowledge>
    </fwb-tab>
  </fwb-tabs>
   
</template>

<style>
</style>
