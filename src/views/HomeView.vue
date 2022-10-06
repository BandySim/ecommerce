<template>
  <v-app>
    <NavbarComponents class="index"/>
    <DashboardComponents/>
    <FooterComponents />
  </v-app>
</template>

<script>
// @ is an alias to /src
import NavbarComponents from '@/components/Navbar-components.vue';
import DashboardComponents from '@/components/Dashboard-components.vue';
import FooterComponents from '@/components/Footer-components.vue';

export default {
  name: 'HomeView',

  components: {
    NavbarComponents,
    DashboardComponents,
    FooterComponents
}
}
</script>
