<template>
  <div class="titolo">
      <h1>La mia prima app con Vue CLI!</h1>
      <div class="immag">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcTjY4lBrgBYLInrKCfWwpv9PGxVvUfEFpDskQ&usqp=CAU" alt="">
      </div>
  </div>
</template>

<script>
export default {
    nome: 'Title'
}
</script>

<style>

div.titolo{
  color: darkorange;
}
.immag{
  width: 70%;
}
.immag img{
  width: 100%;
  border-radius: 10px;
}


</style>