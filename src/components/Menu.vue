<template>
  <section id="menu">
    <nav>
      <ul class="ul-menu">
        <li><a href="#" class="a-menu">SMARTPHONES</a></li>
        <li><a href="#" class="a-menu">TABLETS</a></li>
        <li><a href="#" class="a-menu">ORDENADORES</a></li>
        <li><a href="#" class="a-menu">CONSOLAS</a></li>
        <li><a href="#" class="a-menu">ACCESORIOS</a></li>
      </ul>
    </nav>
  </section>
</template>

<script>
export default {};
</script>

<style>
#menu {
    z-index:999;
}
nav {
  display: flex;
  flex-direction: column;
  background-color: #cde2e1;
}
a.a-menu {
  text-decoration: none;
  font-family: 'Source Sans Pro', sans-serif;
  font-size: 1.5rem;
  color: #11151C;
}
a.a-menu:hover{
    color:rgb(123, 167, 164);
}
.ul-menu {
  display: flex;
  flex-direction: row;
  list-style: none;
  align-self: center;
}
.ul-menu li {
  padding-right: 2.5rem;
  padding-left: 2.5rem;
  height: 100%;
}
</style>