<!-- App.svelte -->
<script>
  import { Router, Link, Route } from "svelte-routing";
  import SoftwareDeveloper from "./routes/SoftwareDeveloper.svelte";
  import GameDeveloper from "./routes/GameDeveloper.svelte";


  export let url = "";
</script>

<Router {url}>
  <nav>
    <Link to="/">Home</Link>
    <Link to="/game">Game</Link>
  </nav>
  <div>
    <Route path="/"><SoftwareDeveloper /></Route>
    <Route path="/game"><GameDeveloper/></Route>
  </div>
</Router>