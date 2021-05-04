<script>
  import { Route } from "tinro";
  import Home from "./lib/Home.svelte";
  import About from "./lib/About.svelte";
  import Navigation from "./lib/Navigation.svelte";
</script>

<main>
  <Navigation />
  <div class="row is-center">
    <div class="col-10 col-5-md">
      <Route path="/">
        <Home />
      </Route>
      <Route path="/about">
        <About />
      </Route>
    </div>
  </div>
</main>
