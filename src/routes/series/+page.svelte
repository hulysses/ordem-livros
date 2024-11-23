<script>
  import ItemSerie from "../../components/serie/ItemSerie.svelte";
  import Titulo from "../../components/shared/Titulo.svelte";
  import series from "../../constants/series";
</script>

<div class="flex flex-col gap-10">
  <Titulo
    tituloPrincipal="Autores"
    tituloSecundario="Conheça os autores das histórias que você ama."
  />

  <div class="grid grid-cols-2 gap-5">
    {#each series as serie}
      <ItemSerie {serie} />
    {/each}
  </div>
</div>
