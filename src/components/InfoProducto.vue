<template>
  <section id="info-producto">
      <h1>Samsung Galaxy A52s 5G</h1>
      <h3>128GB, 6GB RAM, Verde Menta</h3>
      <h2>339€</h2>
      <p>IVA incluido</p><br>

      <div class="sel">
      <div class="wrapper">
        <button class="btn" @click="cambiarNumero('-1')" type="button" name="button">-</button>
        <input type="text" class="unidades" name="name" :value="contador">
        <button class="btn" @click="cambiarNumero('1')" type="button" name="button">+</button>
      </div><br>

      <button class="comprar">Añadir al carrito</button>
      </div>
  </section>
</template>

<script>
export default {
  Name: 'InfoProducto',
    data(){
      return {
        contador: 1
      }
    },
    methods: {
      cambiarNumero(num){
        this.contador+= +num;
        if(!isNaN(this.contador) && (this.contador < 0)){
          this.contador = 0
        }
      }
    }
}
</script>

<style>
  #info-producto h1{
    font-size: 2rem;
    margin-bottom: 0;
  }

  #info-producto h3{
    font-weight: 200;
    margin-top: 0.5rem;
  }

  #info-producto h2{
    font-size: 2.5rem;
    margin:0;
  }

  #info-producto p {
    font-weight: 200;
    margin-top: 0.5rem;
  }

  .sel {
    display: flex;
    flex-direction: row;
    align-items: center;
  }
  .wrapper {
    height: 1.5rem;
    display: flex;
    padding-right: 2rem;
  }

  .unidades {
    width: 1.5rem;
    text-align: center;
    font-size: 1rem;
    border: none;
  }

  .btn {
    width: 2rem;
    font-weight: 500;
    border: none;
    background-color: #cde2e1;
  }

  .btn:hover{
    cursor: pointer;
  }

  .comprar {
    height: 2.5rem;
    width: 10rem;
    font-size: 1rem;
    border:none;
    border-radius: 5rem;
    background-color: #83bebb;
  }

  .comprar:hover{
    cursor: pointer;
  }
</style>