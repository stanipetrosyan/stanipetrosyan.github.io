<script>
  import { Card, Button, Avatar } from 'flowbite-svelte';
  export let img = "";
  export let name = "";
  export let description = "";
  export let link = "/"
</script>

<div>
  <Card padding="sm" href={link}>
    <div class="flex flex-col items-center pb-4">
      <Avatar size="lg" src={img} />
      <h5 class="mb-2 text-2xl font-bold tracking-tight text-gray-900 dark:text-white">{name}</h5>
      <p class="mb-3 font-normal text-gray-700 dark:text-gray-400 leading-tight">{description}</p>
    </div>
  </Card>
</div>

