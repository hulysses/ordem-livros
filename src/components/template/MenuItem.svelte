<script>
  export let url = "/";
  export let texto = "";
</script>

<li>
  <a
    href={url}
    class="flex gap-2 items-center cursor-pointer px-4 py-2 text-zinc-300
    hover:underline hover:text-white hover:bg-white/10"
  >
    <slot />
    <span>{texto}</span>
  </a>
</li>
