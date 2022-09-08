<template>
<div class="form">
  <form action="post" class="formulario">
    <div>
    <input type="text" id="provincia" v-model="provincia" placeholder="digite a provincia..."/>
    <input type="submit" class="butao" value="escolha a provincia"/>
  </div>
  </form>
</div>
<di class="app1">
<div class="app2" >
  <h1>Maputo</h1>

  <img class="aa" alt="vue logo" src="../assets/333.png"/>

  
  <div class="bb">
      <p> maxima = 33</p>
      <p> minima = 16</p>
    </div>
</div>

<div class="app2" >
  <h1>Maputo</h1>

  <!-- <img class="aa" alt="Vue logo" src="./assets/a.webp"/> -->
  <img class="aa" alt="vue logo" src="../assets/images.png"/>

 
  <div class="bb">
      <p> maxima = 33</p>
      <p> minima = 16</p>
    </div>
</div>

<div class="app2" >
  <h1>Maputo</h1>

  <img class="aa" alt="vue logo" src="../assets/logo.png"/>

 
  <div class="bb">
      <p> maxima = 33</p>
      <p> minima = 16</p>
    </div>
</div>

</di>
  </template>
  
  <script>
    // import card1 from './card1.vue'
  
  export default {
    name: 'App',
    components: {
      // card1
    }
  }
  </script>
  
  <style>

  .app1{
  height:"1000px" ;
  width: "100px" ;
  background: "blue";
  display: flex;
  text-align: center;
  margin: 20px;
  padding: 50px;

}

.app2{
  height:"100px" ;
  width: "100px" ;
  background-color: "blue";
  padding: 20px;

}

.aa{
  height:"20px" ;
  width: "20px" ;
}

.form{
  display: flex;
  align-items: center;
  justify-content: center;
  padding-bottom: 40px;
}
.formulario{
    display: flex;
}

.bb{
  display: flex;
}
  </style>