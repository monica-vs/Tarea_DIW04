<template>
  <section id="descripcion-producto">
    <div id="dp-div"></div>

    <div id="desc-div">
      <h1>Características</h1>
      <br>
      <ul>
        <h2>Máximo rendimiento</h2>
        <li>La tecnología 5G es la vanguardia de la conectividad móvil, y te permite transmitir contenido en calidad UHD y una velocidad de descarga hasta 20 veces mayor</li>
        <li>Su nuevo procesador Snapdragon 778G de 6nm ofrece un rendimiento excepcional en procesamiento de imágenes y gaming</li>
        <li>No te quedes sin espacio gracias a los 128/256Gb de almacenamiento ampliables hasta 1Tb por microSD</li>
        <h2>Cámara impresionante</h2>
        <li>Con una cámara principal de 64MP captura todos los detalles y gracias al Estabilizador Óptico de Imagen (OIS) tus fotos y vídeos tendrán una nitidez sorprendente.</li>
        <li>Congela el momento exacto. Graba videos en 4K y extrae fotos en 8MP del momento exacto que quieras.</li>
        <h2>Pantalla de ensueño</h2>
        <li>Su espectacular pantalla Super AMOLED cuenta con hasta 800nit de brillo y 1M:1 de contraste. Combínalo con el sonido estéreo con Dolby Atmos para disfrutar de tus videos y contenidos favoritos en cualquier lugar.</li>
        <li>La Tasa de refresco de 120Hz ofrece imágenes más fluidas y detalladas. Además la respuesta táctil también aumenta para que puedas jugar de forma más precisa.</li>
        <li>Con 6,5” su diseño Infinity-O aprovecha mejor el frontal y además es más resistente gracias a la protección Gorilla Glass 5.</li>
        <h2>Imparable</h2>
        <li>Alta capacidad de batería con 4.500 mAh. Para que puedas llegar a los 2 días de autonomía.</li>
        <li>Carga Ultra Rápida de 25W para que en apenas 30min cargues más del 50% de la batería. </li>
        <h2>Resistencia</h2>
        <li>Impresionante, con Galaxy A52s 5G no tendrás que preocuparte por nada, ni por los accidentes de agua ya que es resistente a polvo y agua.</li>
        <li>Su certificado de resistencia IP67 al polvo y agua te permite usarlo en todo tipo de entornos, sin restricciones ni preocupaciones. Puedes sumergirlo en 1m de agua durante 30min.</li>
      </ul>
      <iframe width="560" height="315" src="https://www.youtube.com/embed/hnWfwi4h1KU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </section>
</template>

<script>
export default {

}
</script>

<style>
#descripcion-producto{
  display: flex;
  flex-direction: row;
}

#dp-div{
  width: 20%;
}

#desc-div{
  display: flex;
  flex-direction: column;
  padding-right: 25rem;
}

#desc-div h1{
  font-size: 1.7rem;
  margin: 0;
  color: #1bb1a9;
}

#desc-div h2{
  font-size: 1rem;
}

#desc-div ul{
  margin-bottom: 3rem;
}

#desc-div iframe{
  align-self: center;
  margin-left: 15rem;
  margin-bottom: 3rem;
}
</style>