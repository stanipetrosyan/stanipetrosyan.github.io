<script setup>
import { FwbButton, FwbAvatar, FwbHeading } from 'flowbite-vue';

defineProps(['img', 'name', 'link', 'color'])

</script>

<template>
  <div>
    <fwb-button :href=link outline :gradient=color square>
      <div class="flex flex-col items-center">
        <fwb-avatar size="lg" :img=img />
        <fwb-heading tag="h6" class="text-white">{{ name  }}</fwb-heading>
      </div>

    </fwb-button>
  </div>
</template>
