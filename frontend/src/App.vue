<script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="https://vite.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />

  <div class="container">
      <!--This is for text box #1-->
        <input text="text" placeholder= "Enter code: ">
      <!--Box numero 2-->
        <input text="text" placeholder= "output ig: ">
    </div>

    <div class="d-grid">
      <button type="submit" class="submit-btn">Submit</button>
    </div>
</template>


<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
.container{
  display: flex;
  justify-content: space-between;
  width: 100%;
  padding: auto;
  gap: 40px;
  
}
/*PLEASE BE THE PERFECT SIZE BESTIE(idk if i like having style and html here.........sus... >-<)*/
input{
  width: 300px;
  height: 300px;
  padding: auto;
  font-size: 16px;
  border-radius: 5px;
  border: 3px solid;
}
.submit-btn{
  margin-top: 10px;
  padding: 10px 20px;
  cursor: pointer;
}


</style>
