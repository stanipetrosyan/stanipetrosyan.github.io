<script>
  import { Card, Button, Avatar, GradientButton, Heading } from 'flowbite-svelte';
  export let img = "";
  export let name = "";
  export let link = "/"
  export let color = "pinkToOrange"
</script>

<div>
  <GradientButton href={link} outline color={color}>
     <div class="flex flex-col items-center">
      <Avatar size="lg" src={img} />
      <Heading tag="h6">{name}</Heading>
    </div>
   
  </GradientButton>
</div>

