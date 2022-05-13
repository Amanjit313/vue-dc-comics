<template>
<div class="myHeader">

  <img src="../assets/img/dc-logo.png" alt="DC_Logo">

  <nav>
    <ul>
      <li><a href="#">Characters</a></li>
      <li><a href="#" class="isActive">Comics</a></li>
      <li><a href="#">Movies</a></li>
      <li><a href="#">Tv</a></li>
      <li><a href="#">Games</a></li>
      <li><a href="#">Collectibles</a></li>
      <li><a href="#">Videos</a></li>
      <li><a href="#">Fans</a></li>
      <li><a href="#">News</a></li>
      <li><a href="#">Shop</a></li>
    </ul>
  </nav>

</div>
</template>

<script>
export default {
  name: "myHeader"
}
</script>

<style lang="scss">

.myHeader{
  display: flex;
  background-color: antiquewhite;
  align-items: center;
  justify-content: space-between;
  width: 70%;
  margin: 0 auto;
}

.myHeader img{
  padding: 10px;
  width: 6rem;
}

.myHeader ul{
  display: flex;
  list-style: none;
  height: 100%;
}

.myHeader li{
  text-decoration: none;
  text-transform: uppercase;
  height: 100%;
  padding: 0px 10px;
}

.myHeader a{
  text-decoration: none;
  color: black;
  font-size: .9rem;
  border-bottom: 4px solid transparent;
  padding: 35px 0px;

  &.isActive{
    color: #0282F9;
    border-bottom: 4px solid #0282F9;
  }
}


</style>