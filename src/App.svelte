<!-- App.svelte -->
<script>
  import { Router, Link, Route } from "svelte-routing";
  import SoftwareDeveloper from "./routes/SoftwareDeveloper.svelte";
  import GameDeveloper from "./routes/GameDeveloper.svelte";
  import Home from "./routes/Home.svelte";
  import { DarkMode } from "flowbite-svelte";
  import { Button } from "flowbite-svelte";
  import { Breadcrumb, BreadcrumbItem } from "flowbite-svelte";

  export let url = "";
</script>

<Router {url}>
  <div class="flex flex-row m-8">
    <div class="place-self-start">
      <Breadcrumb>
        <BreadcrumbItem href="/" home>Home</BreadcrumbItem>
      </Breadcrumb>
    </div>
    <div>
      <Route path="/"><Home /></Route>
      <Route path="/software"><SoftwareDeveloper /></Route>
      <Route path="/game"><GameDeveloper /></Route>
    </div>

    <div class="place-self-start">
      <DarkMode />
    </div>
  </div>
</Router>
