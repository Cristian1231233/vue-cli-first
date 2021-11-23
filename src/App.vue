<template>
  <div class="container">
    <Header />
    <Title />
    
    <Main />
    <Footer />
  </div>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
  import Header from './components/Header.vue'
  import Title from './components/Title.vue'
  import Main from './components/main.vue'
  import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Title,
    Main,
    Footer
    
  }
}
</script>

<style>
.container{
  border: 2px solid black;
}
div{
  text-align: center;
  background: slateblue;
  width: 60%;
  margin: 30px auto;
  border-radius: 20px;
  padding: 10px;
  
  
}

</style>
