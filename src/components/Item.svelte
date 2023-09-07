<script>
  import { Card, Button, Avatar } from 'flowbite-svelte';
  export let img = "";
  export let name = "";
</script>

<div>
  <Card padding="sm">
    <div class="flex flex-col items-center pb-4">
      <Avatar size="lg" src={img} />
      <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">{name}</h5>
      <p class="mb-3 font-normal text-gray-700 dark:text-gray-400 leading-tight">Here are the biggest enterprise technology acquisitions of 2021 so far, in reverse chronological order.</p>
    </div>
  </Card>
</div>

