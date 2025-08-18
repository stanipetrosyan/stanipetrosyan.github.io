<script setup>
import { ref } from 'vue'
import { FwbTab, FwbTabs } from 'flowbite-vue'
import Experience from '@/components/Experience.vue';
import Knowledge from '@/components/Knowledge.vue';

const activeTab = ref('experience')
</script>

<template>
  <div class="flex flex-row">
    <div class="basis-full m-8">
      <fwb-tabs v-model="activeTab" variant="underline">
        <fwb-tab name="experience" title="Experience">
          <Experience></Experience>
        </fwb-tab>
        <fwb-tab name="knowledge" title="Knowledge">
          <Knowledge></Knowledge>
        </fwb-tab>
      </fwb-tabs>
    </div>
  </div>

</template>

<style></style>
