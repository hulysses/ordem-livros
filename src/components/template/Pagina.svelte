<script>
  import Cabecalho from "./Cabecalho.svelte";
  import Rodape from "./Rodape.svelte";
</script>

<div class="flex flex-col min-h-screen bg-black text-white">
  <main class="flex-1">
    <Cabecalho />
    <Rodape />
    <slot />
  </main>
</div>
