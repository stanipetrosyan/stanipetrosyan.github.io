<script lang="ts">
  import { Tabs, TabItem, Button, Heading } from "flowbite-svelte";
  import Games from "../pages/Games.svelte";
</script>

<main>
  <div class="flex flex-row">
    <div class="basis-full m-16">
      <Tabs
        tabStyle="pill"
        defaultClass="flex divide-x rtl:divide-x-reverse divide-gray-200 dark:divide-gray-700"
      >
        <TabItem open class="w-full">
          <span slot="title" class="text-lg">Games</span>
          <Games />
        </TabItem>
      </Tabs>
    </div>
  </div>
</main>

<style>
</style>
