<template>
  <app-nav></app-nav>
  <app-side-nav></app-side-nav>
</template>


<script>

import AppSideNav from './components/Layers/AppSideNav.vue';
import AppNav from './components/Layers/AppNav.vue';


export default {
  components : {
    AppNav,
    AppSideNav
  },
}
</script>