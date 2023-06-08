<template>
  <nav class="navbar">
    <div class="geral">
      <ul class="conteudo">
        <a class="lista" href="">Home</a>
        <a class="lista" href="">Sobre</a>
        <a class="lista" href="">Projetos</a>
      </ul>
      <div id="btn">
        <button class="button">Contate-Me</button>
      </div>
    </div>
  </nav>
</template>

<style scoped>
.geral{
  display: flex;
  align-items: center;
  flex-direction: row;
}
nav{
  background-color: #11367d;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  gap: 1rem;
  height: 4vw;
}
#btn{
  position: absolute;
  left: 90vw;
}
.conteudo{
  display: flex;
  flex-direction: row;
  align-items: center;
  left: 50.5em;
  position: absolute;
}
.lista{
  padding: 1em 0.7em;
}
.lista:hover{
  background-color: #0a1f49;
  border-bottom: 5px solid white;
}
a{
  color: white !important;
  font-family: 'Roboto', sans-serif;
  font-size: 1.3em;
  font-weight: bold;
}
</style>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "Navbar",

})
</script>