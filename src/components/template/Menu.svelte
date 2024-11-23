<script>
  import MenuItem from "./MenuItem.svelte";
  import MenuItens from "./MenuItens.svelte";
</script>

<aside
  class="flex flex-col gap-10 self-start border border-zinc-800 p-5 rounded-md w-72"
>
  <MenuItens titulo="Navegação">
    <MenuItem texto="Início" />
    <MenuItem texto="Personagens" />
    <MenuItem texto="Autores" />
    <MenuItem texto="Séries" />
  </MenuItens>
  <MenuItens titulo="Principais autores">
    <MenuItem texto="Akira Toriyama" />
    <MenuItem texto="Eiichiro Oda" />
    <MenuItem texto="Masashi Kishimoto" />
  </MenuItens>
  <MenuItens titulo="Outras categorias">
    <MenuItem texto="Últimas notícias" />
    <MenuItem texto="Séries populares" />
    <MenuItem texto="Facebook" />
    <MenuItem texto="Instagram" />
    <MenuItem texto="YouTube" />
  </MenuItens>
</aside>
