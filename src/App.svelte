<script lang="ts">
  import Tabs from "./Tabs.svelte";
  import About from "./About.svelte";
	import Knowledge from "./Knowledge.svelte";

  let items = [
    { label: "About Me",
		 value: 1,
		 component: About
		},
    { label: "Knowledge",
		 value: 2,
		 component: Knowledge
		}
  ];
</script>

<main>
  <x-grid columns=8>
    <x-cell span="4..">
      <h1 start animation=fadein ease=easeInOutQuad style="--duration: 2s; --delay: 1s;">Welcome, I'm Stanislav</h1>
    </x-cell>
  </x-grid>

  

  <x-grid columns=8>
    <x-cell span="2-7">
      <Tabs {items}></Tabs>
    
    </x-cell>
  </x-grid>
</main>

<style>
  
</style>
