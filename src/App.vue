<template>
  <div>
    <Header />
    <Title />
    
    <main></main>
    <footer></footer>
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
  import Header from './components/Header.vue'
  import Title from './components/Title.vue'
export default {
  name: 'App',
  components: {
    Header,
    Title
    
  }
}
</script>

<style>
div{
  text-align: center;
}

</style>
