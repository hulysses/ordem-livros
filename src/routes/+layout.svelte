<script lang="ts">
  import "../app.css";
  let { children } = $props();
  import Logo from "../components/template/Logo.svelte";
</script>

<div
  class="bg-black flex flex-col justify-center items-center min-h-screen text-white"
>
  <Logo />
  {@render children()}
</div>
