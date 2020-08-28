
<script>
  import { params } from '@sveltech/routify'
</script>

<header>
  <div class="wrap">
    <h1 class="main-title">ABOUT PAGE</h1>
    <p>페이지 소개 : svelte 강좌 소개 페이지 입니다. </p>   
    <p>Params: {$params.id}</p>
  </div>
</header>