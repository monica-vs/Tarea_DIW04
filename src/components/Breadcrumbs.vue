<template>
  <section id="breadcrumb">
      <a href="#">Inicio</a> >
      <a href="#">Smartphones</a> >
      <a href="#" class="posactual">Samsung</a>
  </section>
</template>

<script>
export default {

}
</script>

<style>
#breadcrumb {
    padding: 2rem;
}
#breadcrumb a {
    font-size: 1.2rem;
    color: #35a09b;
    padding-right: 0.5em;
    padding-left: 0.5em;
}
.posactual {
    font-weight: 800;
}
</style>