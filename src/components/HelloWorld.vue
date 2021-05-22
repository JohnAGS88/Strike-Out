<template>
  <div class="hello">
    <nav class="navbar  bg-dark">
      <a class="navbar-brand" href="#"></a>
    </nav>
    <h1>{{ msg }}</h1> 
  </div>
  <main class="container">
    <div class="row" style="padding-top: 100px">
        <div class="col">
            <input data-date-format="dd/mm/yyyy" id="datepicker">
        </div>
    </div>
</main>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}

</script>

<!-- Para Estilos -->
<style scoped>

</style>
