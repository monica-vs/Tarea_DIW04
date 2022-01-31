<template>
  <section id="imagenes-producto">
      <div class="imagen-principal">
          <img v-bind:src="fotos[0]" alt="Samsung Galaxxy A52s 5G">
      </div>
      <div class="imagen-peq">
          <a @click="cambiarImg(1)"><img v-bind:src="fotos[1]" alt="Samsung Galaxy A52s 5G" copyright="cc-by"></a>
          <a @click="cambiarImg(2)"><img v-bind:src="fotos[2]" alt="Samsung Galaxy A52s 5G" copyright="cc-by"></a>
          <a @click="cambiarImg(3)"><img v-bind:src="fotos[3]" alt="Samsung Galaxy A52s 5G" copyright="cc-by"></a>
          <a @click="cambiarImg(4)"><img v-bind:src="fotos[4]" alt="Samsung Galaxy A52s 5G" copyright="cc-by"></a>
      </div>
  </section>
</template>

<script>
export default {
    Name: 'ImagenesProducto',
    data () {
        return {
            fotos: [
                require ('../assets/img0.png'),
                require ('../assets/img0.png'),
                require ('../assets/img1.png'),
                require ('../assets/img2.png'),
                require ('../assets/img3.png')
            ]
        }
    },
    methods: {
        cambiarImg(id){
            this.fotos[0] = this.fotos[id]
        }
    }
}
</script>

<style>
    #imagenes-producto{
        align-items: center;
        width: 50%;
    }
    .imagen-principal {
        text-align: right;
    }
    .imagen-principal img{
        height:30em;
    }
    .imagen-peq {
        padding: 2rem;
        margin-right: 2.5rem;
        text-align: right;
    }
    .imagen-peq img{
        height: 6rem;
    }
</style>