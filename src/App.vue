<template>
  <header>
    <icon-logo />
    <FilmIcon class="h-5 w-5 fill-blue-300 stroke-blue-600" />
    <nav>
      <RouterLink to="/" class="text-blue-600 underline">Accueil</RouterLink>
    </nav>
    <menu-logo>
      
    </menu-logo>
  </header>

  <RouterView />
</template>

<script>
import IconLogo from "./components/icons/IconLogo.vue";
import { FilmIcon } from "@heroicons/vue/outline";
import { MenuIcon} from "@heroicons/vue/outline";
export default {
  components: { IconLogo, FilmIcon },
  components: { IconLogo, MenuIcon },
};
</script>