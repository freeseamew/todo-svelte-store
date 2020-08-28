<script>
  import { route } from "@sveltech/routify";
  console.log("route", $route);
</script>
<header>
  <div class="wrap">
    <h1>404: missing</h1>
    <p>The path <code>{$route.leftover}</code> was not found.</p>
  </div>
</header>