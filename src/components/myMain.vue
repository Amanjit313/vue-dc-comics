<template>

  <main>
    <div class="main-container jumbotron">
      <img src="../assets/img/jumbotron.jpg" alt="jumbotron-img">
    </div>
    <div>
      <myCardsDC />
    </div>
  </main>

</template>

<script>
import myCardsDC from './myCardsDC.vue';

export default {
  name: "myMain",
  components: {myCardsDC}
}
</script>

<style lang="scss" scoped>

main{
  background-color: #1C1C1C;
  align-items: center;
}

img{
  width: 100%; 
  height: 350px; 
  object-fit: cover;
  object-position: 0% 0%;
}

.jumbotron{
  background-color: purple;
  height: 100px;
  width: 100%;
}

</style>