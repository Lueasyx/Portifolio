<template>
  <nav>
    <ul><a href="">Home</a></ul>
    <ul><a href="">Sobre</a></ul>
    <ul><a href="">Projetos</a></ul>
  </nav>
</template>

<style scoped>
nav{
    background-color: #11367d;
}
</style>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Navbar",

})
</script>