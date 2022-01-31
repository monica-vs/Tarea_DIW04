<template>
  <footer id="pie">
      <div id="sobre">
        <p class="titulo-pie">Sobre Tecnoshop</p>
        <a href="#" class="enlace-pie">¿Quiénes somos?</a><br>
        <a href="#" class="enlace-pie">Condiciones de compra</a><br>
        <a href="#" class="enlace-pie">Aviso legal</a><br>
        <a href="#" class="enlace-pie">Privacidad</a><br>
      </div>
      <div id="ayuda">
        <p class="titulo-pie">Ayuda</p>
        <a href="#" class="enlace-pie">Pagos</a><br>
        <a href="#" class="enlace-pie">Envío</a><br>
        <a href="#" class="enlace-pie">Devoluciones</a><br>
        <a href="#" class="enlace-pie">FAQ</a><br>
      </div>
      <div id="comunidad">
        <p class="titulo-pie">Comunidad</p>
        <a href="#" class="enlace-pie">Facebook</a><br>
        <a href="#" class="enlace-pie">Twitter</a><br>
        <a href="#" class="enlace-pie">Linkedin</a><br>
      </div>
  </footer>
</template>

<script>
export default {

}
</script>

<style>
#pie {
  display: flex;
  flex-direction: row;
  background-color: #202329;
  width: 100%;
  height:30%;
}
#pie div{
  padding-top: 1rem;
  padding-bottom: 2rem;
  padding-left: 2rem;
}
.enlace-pie{
  text-decoration: none;
  color: lightgray;
  padding-left: 0.2rem;
  padding-bottom: 2rem;
}
.enlace-pie:hover{
  color: #FEFCFD;
}
.titulo-pie {
  color: #FEFCFD;
  font-weight: 600;
  font-size: 1.1rem;
  margin-bottom: 0.5rem;
}

</style>