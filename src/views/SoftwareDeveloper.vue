<script setup>
import { ref } from 'vue'
import { FwbTab, FwbTabs } from 'flowbite-vue'
import Experience from '@/components/Experience.vue';
import Knowledge from '@/components/Knowledge.vue';
import Blog from '@/components/Blog.vue';
import Projects from '@/components/Projects.vue';

const activeTab = ref('experience')
</script>

<template>
  <div class="flex flex-row">
    <div class="basis-full m-6">
      <fwb-tabs v-model="activeTab" variant="default">
        <fwb-tab name="experience" title="Experience">
          <Experience></Experience>
        </fwb-tab>
        <fwb-tab name="knowledge" title="Knowledge">
          <Knowledge></Knowledge>
        </fwb-tab>
        <fwb-tab name="blog" title="Blog">
          <Blog></Blog>
        </fwb-tab>
        <fwb-tab name="projects" title="Projects">
          <Projects></Projects>
        </fwb-tab>
      </fwb-tabs>
    </div>
  </div>

</template>

<style></style>
