<template>
  <section class="app-wrapper">
    <header-app>
      <div class="flex  items-center h-full bg-state-500">
        <div class="w-3 text-center text-gray-500">
            Crear
        </div>
        <div class="w-3 text-center text-gray-500">
            Administrar
        </div>
      </div>
    </header-app>
    <div class="flex  items-center h-full bg-state-500">
        <div class="w-3 text-center text-gray-500">
            Crear
        </div>
        <div class="w-3 text-center text-gray-500">
            Administrar
        </div>
      </div>
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Hello Vue 3.0 + Vite" />
    <h1 class="text-3xl font-bold underline">
      Hello HelloWorld
    </h1>
  </section>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HeaderApp from './components/header/main.vue'
export default {
  name: 'App',
  components: {
    HelloWorld,
    HeaderApp
  }
}
</script>
<style lang="css" scoped>
.app-wrapper{
  height: 100vh;
  color: #000000;
  font-size: 14px;
}
</style>