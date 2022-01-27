<template>
  <header>
    <div class="container">
      <div class="logo">
        <img src="../assets/img/dc-logo.png" alt="">
      </div>
      <div class="menu">
        <ul>
          <li v-for="(element, index) in links" :key="index">
            <a href="#">
              {{element.text}}
            </a>
          </li>
        </ul>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header',

data() {
    return{
      links:[
        {
          text: "Carachters",
          url: "#",
          current: false,
        },
        {
          text: "Comics",
          url: "#",
          current: false,
        },
        {
          text: "Movies",
          url: "#",
          current: false,
        },
        {
          text: "TV",
          url: "#",
          current: false,
        },
        {
          text: "Games",
          url: "#",
          current: false,
        },
        {
          text: "Collectibles",
          url: "#",
          current: false,
        },
        {
          text: "Videos",
          url: "#",
          current: false,
        },
        {
          text: "Fans",
          url: "#",
          current: false,
        },
        {
          text: "News",
          url: "#",
          current: false,
        },
        {
          text: "Shop",
          url: "#",
          current: false,
        },
      ]
    }
  }
}


</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../assets/style/partial/variables.scss';

.container{
  display: flex;
  justify-content: space-between;
  align-items: center;
}

li{
  text-transform: uppercase;
  font-weight: bold;
  display: inline-block;
  margin: 0 10px;
  line-height: 150px;

  a{
    color: black;
  }
  a:hover{
    color: $primarycolor;
  }
}

.active{
  border-bottom: 5px solid $primarycolor;
}
</style>
