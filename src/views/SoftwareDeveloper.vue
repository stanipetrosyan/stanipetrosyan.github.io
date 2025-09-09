<script setup>
import Experience from '@/components/software/Experience.vue';
import Knowledge from '@/components/Knowledge.vue';
import Blog from '@/components/Blog.vue';
import Projects from '@/components/Projects.vue';
import Tabs from '@/components/Tabs.vue';

const tabs = {
  Experience,
  Knowledge,
  Projects,
  Blog
}

</script>

<template>
  <Tabs :tabs="tabs"></Tabs>
</template>

<style scoped>
</style>
