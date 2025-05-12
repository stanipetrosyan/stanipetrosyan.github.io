<script lang="ts">
  import { Tabs, TabItem, Button, Heading } from "flowbite-svelte";
  import About from "../pages/About.svelte";
  import Knowledge from "../pages/Knowledge.svelte";
  import Experience from "../pages/Experience.svelte";
  import { DarkMode } from "flowbite-svelte";
</script>

<main>
  <div class="flex flex-row">
    <div class="basis-full m-16">
      <Tabs
        tabStyle="pill"
        defaultClass="flex divide-x rtl:divide-x-reverse divide-gray-200 dark:divide-gray-700">
        <TabItem class="w-full" open>
          <div slot="title" class="text-lg self-center">Ciaoo</div>
          <About />
        </TabItem>
        <TabItem class="w-full">
          <span slot="title" class="text-lg">provvissima</span>
          <Knowledge />
        </TabItem>
        <TabItem class="w-full">
          <span slot="title" class="text-lg">Experience</span>
          <Experience />
        </TabItem>
      </Tabs>
    </div>
  </div>
</main>

<style>
</style>