<script lang="ts">
  import "../app.css";
  let { children } = $props();
  import Pagina from "../components/template/Pagina.svelte";
</script>

<Pagina>
  {@render children()}
</Pagina>
