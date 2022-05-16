<template>

  <main>
    <div class="main-container jumbotron">
      <img src="../assets/img/jumbotron.jpg" alt="jumbotron-img">
    </div>
    <div>
    <p class="current-series-btn w-70"> <a href="#">Current Series</a> </p>
    <div class="myCards-container">
      <myCardsDC />
      <p class="load-more-btn"> <a href="#">Load More</a> </p>
    </div>
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
  position: relative;
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

.current-series-btn{
  bottom: 62%;
  left: 18%;
  position: absolute;
  font-size: 1.1rem;
}

.myCards-container{
  height: 550px;
}

.myCards-container p{
  text-align: center;
  margin-top: 50px;
}

.myCards-container a,
.current-series-btn a{
  color: white;
  background-color: #0282F9;
  padding: 10px 35px;
  margin-bottom: 50px;
  text-transform: uppercase;
}

</style>