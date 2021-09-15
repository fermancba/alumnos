<template>
  <div id="app">
    <img alt="Alumnos logo" src="./assets/alumnos.png" />
    <Alumnos />
    <navegacion></navegacion>
    <div class="container-fluid">
      <registrar-alumno></registrar-alumno>
      <lista-alumnos></lista-alumnos>
    </div>
  </div>
</template>

<script>
import Alumnos from "@/components/Alumnos.vue";
import Navegacion from "@/components/Navegacion.vue";
import RegistrarAlumno from "@/components/RegistrarAlumno.vue";
import ListaAlumnos from "@/components/ListaAlumnos.vue";

export default {
  name: "App",
  components: {
    Alumnos,
    Navegacion,
    RegistrarAlumno,
    ListaAlumnos,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
