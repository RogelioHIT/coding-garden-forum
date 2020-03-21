<template>
  <div id="app">
    <app-nav></app-nav>
    <router-view class="container"></router-view>
  </div>
</template>

<script>
import AppNav from '@/components/AppNav.vue';

export default {
  components: {
    AppNav,
  },
};
</script>
