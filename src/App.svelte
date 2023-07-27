<script lang="ts">
  import { Tabs, TabItem, Button, Heading } from "flowbite-svelte";
  import About from "./About.svelte";
  import Knowledge from "./Knowledge.svelte";
  import Experience from "./Experience.svelte";
  import { DarkMode } from "flowbite-svelte";
</script>

<main>
  <div class="flex flex-row">
    <div class="basis-full">
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
    <div class="place-self-start">
      <DarkMode />
    </div>
  </div>
</main>

<style>
</style>
