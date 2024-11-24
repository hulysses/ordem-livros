<script>
  import {
    IconBooks,
    IconBrandFacebook,
    IconBrandInstagram,
    IconBrandYoutube,
    IconFriends,
    IconHome,
    IconRss,
    IconSquare1,
    IconSquare2,
    IconSquare3,
    IconUsers,
  } from "@tabler/icons-svelte";
  import MenuItem from "./MenuItem.svelte";
  import MenuItens from "./MenuItens.svelte";
</script>

<aside
  class="flex flex-col self-start
 border border-zinc-800 p-5 rounded-md gap-10 w-72"
>
  <MenuItens titulo="Navegação">
    <MenuItem texto="Início" url="/">
      <IconHome size={20} />
    </MenuItem>
    <MenuItem texto="Personagens" url="/">
      <IconFriends size={20} />
    </MenuItem>
    <MenuItem texto="Autores" url="/autores">
      <IconUsers size={20} />
    </MenuItem>
    <MenuItem texto="Séries" url="/">
      <IconBooks size={20} />
    </MenuItem>
  </MenuItens>
  <MenuItens titulo="Principais Autores">
    <MenuItem texto="J.K. Rowling" url="/autores/j-k-rowling">
      <IconSquare1 size={20} />
    </MenuItem>
    <MenuItem texto="J.R.R. Tolkien" url="/autores/j-r-r-tolkien">
      <IconSquare2 size={20} />
    </MenuItem>
    <MenuItem texto="George R.R. Martin" url="/autores/george-r-r-martin">
      <IconSquare3 size={20} />
    </MenuItem>
  </MenuItens>
  <MenuItens titulo="Outras Categorias">
    <MenuItem texto="Últimas Notícias" url="/">
      <IconRss size={20} />
    </MenuItem>
    <MenuItem texto="Séries Populares" url="/">
      <IconBooks size={20} />
    </MenuItem>
    <MenuItem texto="Facebook" url="/">
      <IconBrandFacebook size={20} />
    </MenuItem>
    <MenuItem texto="Instagram" url="/">
      <IconBrandInstagram size={20} />
    </MenuItem>
    <MenuItem texto="Youtube" url="/">
      <IconBrandYoutube size={20} />
    </MenuItem>
  </MenuItens>
</aside>
