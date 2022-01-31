<template>
  <section id="cabecera">
    <div class="cont">
      <a href="#"><img class="img-logo" src="../assets/logo.png" alt="Tecnoshop" copyright="c"/></a>
      <form class="barra-busqueda" @submit.prevent="handleEnviar">
          <input type="text" placeholder="Buscar en Tecnoshop...">
          <button class="boton">Buscar</button>
      </form>
      <div class="areausuario">
        <a href="#"><abbr title="Iniciar sesión"><span class="material-icons icono">person_outline</span></abbr></a>
        <a href="#"><abbr title="Carrito"><span class="material-icons icono">shopping_cart</span></abbr></a>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style>
    .cont {
        display: flex;
        flex-direction: row;
        flex-grow: 1;
        align-items: center;
        justify-content: space-between;
    }
    .img-logo {
        height: 5.5rem;
    }
    .barra-busqueda input {
        padding: 0.5em;
        border-color: #11151C;
        border-width: 1px;
        border-radius: 3rem;
        box-shadow: none;
        width: 25rem;
        margin-right: 0.5rem;
    }
    .boton {
        padding: 0.5em;
        padding-right: 1rem;
        padding-left: 1rem;
        border-radius: 3rem;
        border-width: 1px;
    }

    .boton:hover{
        cursor: pointer;
    }

    .icono {
        padding-left: 0.2rem;
        padding-right: 0.5rem;
        color: #11151C;
    }
    a {
        text-decoration: none;
    }
</style>