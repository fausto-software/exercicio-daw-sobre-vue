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
      <h1>Maputo</h1>
    
      <img class="aa" alt="vue logo" src="./assets/a.webp"/>
    
      <p> maxima = 33</p>
      <p> minima = 16</p>
    </di>
    <di class="app1">
      <h1>Maputo</h1>
    
      <img class="aa" alt="vue logo" src="./assets/a.webp"/>
    
      <p> maxima = 33</p>
      <p> minima = 16</p>
    </di>
    <di class="app1">
      <h1>Maputo</h1>
    
      <img class="aa" alt="vue logo" src="./assets/a.webp"/>
    
      <p> maxima = 33</p>
      <p> minima = 16</p>
    </di>
      </template>
  
  <script>
    //   import HelloWorld from './components/HelloWorld.vue'
      
      export default {
        name: 'App',
        components: {
        //   HelloWorld
        }
      }
      </script>
      
      <style>
      /* #app {
        font-family: Avenir, Helvetica, Arial, sans-serif;
        -webkit-font-smoothing: antialiased;
        -moz-osx-font-smoothing: grayscale;
        text-align: center;
        color: #2c3e50;
        margin-top: 60px; 
      }
      
      .app1{
        height:"20px" ;
        width: "20px" ;
        background: "blue";
      } */
      .app1{
      /* /* height:"1000px" ; */
      width: "1000px" ;
      background: "blue";
      /* display: block; */
      text-align: center;
      background-color: blueviolet;
      /* justify-content: center;
      align-items: center;  */
    }
    .app1 img{
      align-items: center;
      height:"100px" ;
      width: "100px" ;
      padding-left: 480px;
    }
    
    .app2{
      height:"100px" ;
      width: "100px" ;
      background-color: "blue";
      padding: 20px;
    
    }
    
    .aa{
      display: flex;
      align-items: center;
      /* justify-content: center; */
      /* height:"20px" ;
      width: "20px" ; */
  
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
      </style>