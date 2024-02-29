<script>
  import { Router, Route } from "svelte-routing";
  
  import HomePage from "./Home.svelte";
  import YesPage from "./Yespage.svelte";
  import NoPage from "./Nopage.svelte";
</script>

<Router>
  <Route path="/" component={HomePage} />
  <Route path="/yes" component={YesPage} />
  <Route path="/no" component={NoPage} />
</Router>