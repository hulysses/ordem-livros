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
    <div>
      <span>{livro.titulo}</span>
      <button class="botao azul">Link do livro</button>
    </div>
  </a>
{/if}
