<template>
  <HomeView />
  <div>
    <router-view />
  </div>
</template>

<style>

</style>

<script lang="ts">
import { RouterView } from 'vue-router';
import { defineComponent } from 'vue';
import HomeView from './views/HomeView.vue';

export default defineComponent({
  name: 'App',
  components: {
    HomeView,
  }
})
</script>