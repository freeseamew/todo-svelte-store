<script>

  import { url, isActive } from "@sveltech/routify";

  // const links = [
  //   ["/index", "Home"],
  //   ["/about", "About"],
  //   ["/todos", "Todos"],
  //   ["/questions", "Questions"]
  // ];

  let id = "123"

</script>

<nav class="menu-box">
  <!-- {#each links as [path, name]}
    <a href="{$url(path)}" class:located={$isActive(path)}>{name} + {path}</a>
  {/each} -->

  <a href="{$url('/index')}" class:located={$isActive('./index')} class="btn" >Home</a>
  <a href={$url('/about/:id', {id: id} )} class:located={$isActive('./about')} class="btn">About</a>
  <a href="{$url('./todos')}" class:located={$isActive('./todos')} class="btn">Todos</a>
  <a href="{$url('./posts')}" class:located={$isActive('./posts')} class="btn">Posts</a>

</nav>