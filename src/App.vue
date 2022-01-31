<template>
  <Cabecera />
  <Menu />
  <div class="contenedor">
    <Breadcrumbs />
    <div class="producto">
      <ImagenesProducto />
      <InfoProducto />
    </div>
  </div>
  <DescripcionProducto />
  <Pie />
</template>

<script>
import Cabecera from './components/Cabecera.vue'
import Menu from './components/Menu.vue'
import Breadcrumbs from './components/Breadcrumbs.vue'
import ImagenesProducto from './components/ImagenesProducto.vue'
import InfoProducto from './components/InfoProducto.vue'
import DescripcionProducto from './components/DescripcionProducto.vue'
import Pie from './components/Pie.vue'

export default {
  name: 'App',
  components: { Cabecera,
                Menu,
                Breadcrumbs,
                ImagenesProducto,
                InfoProducto,
                DescripcionProducto, Pie
                
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Source+Sans+Pro:wght@200;300;400;600;700&display=swap');
html {
  background-color: #FEFCFD;
}
body {
  margin: 0;
}

#app {
  font-family: 'Source Sans Pro', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
.contenedor {
  display:flex;
  flex-direction: column;
}
.producto {
  display: flex;
  flex-direction: row;
}
</style>
