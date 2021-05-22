<template>
  <HelloWorld msg="Bienvenidos a Strike-Out App"/>
  <form class="shadow-lg p-3 mb-5 bg-white rounded">
  <div class="form-row">
    <div class="col-md-5 mb-3"></div>
    <div class="col-md-2 mb-3">
      <label for="validationServer"></label>
      <input type="text" class="form-control is-valid" id="validationServer02" placeholder="Nombre y Apellido"  required>
      <div class="valid-feedback">
        Ingrese Sus Datos
      </div>
    </div>
    <div class="col-md-4 mb-3"></div>
  </div>
  <button class="btn btn-dark" type="submit">Aceptar</button>
</form>
  <datepicker></datepicker>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Datepicker from 'vuejs-datepicker';

export default {
  name: 'App',
  components: {
    HelloWorld,
    Datepicker
  }
}
</script>

<style>
#app {
  font-family: 'Nunito', sans-serif; 
  text-align: center;
  color: #072b50;
}

</style>
