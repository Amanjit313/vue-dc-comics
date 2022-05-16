<template>

  <header>
    <div class="header-container w-70">
      <img src="../assets/img/dc-logo.png" alt="dc-logo">
      <ul>
        <li v-for="(options, index) in menu" :key="`menu-${index}`">
          <a :class="{'menuActive' : options.isActive}" :href="options.href">{{options.select}}</a>
        </li>
      </ul>
    </div>
  </header>

</template>

<script>
export default {
  name: "myHeader",
  data(){
    return{
      menu: [
        {
          select: "Characters",
          href: "#",
          isActive: false
        },
        {
          select: "Comics",
          href: "#",
          isActive: true
        },
        {
          select: "Movies",
          href: "#",
          isActive: false
        },
        {
          select: "Tv",
          href: "#",
          isActive: false
        },
        {
          select: "Games",
          href: "#",
          isActive: false
        },
        {
          select: "Collectibles",
          href: "#",
          isActive: false
        },
        {
          select: "Videos",
          href: "#",
          isActive: false
        },
        {
          select: "Fans",
          href: "#",
          isActive: false
        },
        {
          select: "News",
          href: "#",
          isActive: false
        },
        {
          select: "Shop",
          href: "#",
          isActive: false
        }
      ]
    }
  }
}
</script>

<style lang="scss" scoped>

.header-container{
  display: flex;
  align-items: center;
  justify-content: space-between;
  margin: 0 auto;
}

.header-container img{
  padding: 10px;
  width: 6rem;
}

.header-container ul{
  display: flex;
  height: 100%;
}

.header-container li{
  text-decoration: none;
  text-transform: uppercase;
  height: 100%;
  padding: 0px 10px;
}

.header-container a{
  color: black;
  font-size: .9rem;
  border-bottom: 4px solid transparent;
  padding: 35px 0px;

  &.menuActive{
    color: #0282F9;
    border-bottom: 4px solid #0282F9;
  }

  &:hover{
    color: #0282F9;
  }
}

</style>