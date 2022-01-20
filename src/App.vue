<template>
  <main>
   
    <buttom class="boton_uno"/> 
    <buttom class="boton_dos"/> 
    <buttom class="boton_tres"/> 
    <br>
    <buttom class="boton_cuatro"/> 
    <buttom class="boton_cinco"/> 
    <buttom class="boton_seis"/> 
     <br>
    <buttom class="boton_siete"/> 
    <buttom class="boton_ocho"/> 
    <buttom class="boton_nueve"/> 
    <br>
    <buttom class="boton_diez"/> 
    <buttom class="boton_once"/> 
    
    
  </main>
</template>

<script>

import buttom from "@/components/buttom";


export default {
  name: "App",
  components: {  buttom },
};
</script>

<style>
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
