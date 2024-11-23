<script>
  import Cabecalho from "./Cabecalho.svelte";
  import Menu from "./Menu.svelte";
  import Rodape from "./Rodape.svelte";
</script>

<div class="flex flex-col min-h-screen bg-black text-white">
  <Cabecalho />
  <div class="flex flex-1 max-w-7xl mx-auto w-full p-5">
    <main class="flex-1">
      <slot />
    </main>
    <Menu />
  </div>
  <Rodape />
</div>
