<script>
  import { Router, Route } from "svelte-routing";
  import MainPage from './pages/mainPage/MainPage.svelte'
  export let url = "";
</script>

<Router url="{url}">
    <Route path="/"><MainPage /></Route>
</Router>



<style>

</style>