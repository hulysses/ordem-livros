<script>
  import ItemAutor from "../../components/autor/ItemAutor.svelte";
  import autores from "../../constants/autores";
</script>

<div class="grid grid-cols-2 gap-5">
  {#each autores as autor}
    <ItemAutor {autor} />
  {/each}
</div>
