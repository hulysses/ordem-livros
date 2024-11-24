<script lang="ts">
  export let livro: any = null;
</script>

{#if livro}
  <a
    href={livro.link}
    target="_blank"
    class="flex flex-col rounded-md overflow-hidden bg-zinc-800"
  >
    <img src={livro.imagem} alt="Imagem do livro" class="w-96" />
    <div class=" flex-1 flex flex-col p-5 gap-5">
      <span class="flex-1 font-semibold text-center">{livro.titulo}</span>
      <button class="botao azul">Link do livro</button>
    </div>
  </a>
{/if}
