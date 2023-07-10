<script lang="ts">
  import { Tabs, TabItem, Button, Heading } from "flowbite-svelte";
  import About from "./About.svelte";
  import Knowledge from "./Knowledge.svelte";
  import Experience from "./Experience.svelte";
  import { DarkMode } from 'flowbite-svelte';
</script>

<main>
  <div class="grid grid-rows-6 grid-cols-6">
    <div class="col-start-6 row-start-1">
      <DarkMode/>
    </div>
    <div class="col-start-2 row-start-2 row-span-1">
      <Heading tag="h1" class="mb-4">Welcome</Heading>
    </div>
    <div class="col-start-2 col-span-3 row-start-3 row-span-2">
      <Tabs style="underline">
        <TabItem open title="About">
          <About />
        </TabItem>
        <TabItem title="Knowledge">
          <Knowledge />
        </TabItem>
        <TabItem title="Experience">
          <Experience />
        </TabItem>
      </Tabs>
    </div>
  </div>
</main>

<style>
</style>
