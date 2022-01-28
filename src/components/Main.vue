<template>
  <main>
    <div class="jumbotron">
    </div>
    <div class="container">
      <a href="#" class="current">
        Current series
      </a>
      <div class="container2">
        <fumetto 
        v-for="(element, index) in comics" :key="index"
        :thumb="element.thumb"
        :series= "element.series"
        />
      </div>
      <button class="show">
        Load more
      </button>
    </div>
  </main>
</template>

<script>
import fumetto from "./fumetto.vue"
import comicsdata from "../data/comics-data"
export default {
  name: 'Main',
  
  components: {
    fumetto
  },
  data(){
    return {
      comics:comicsdata
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../assets/style/partials/variables.scss';

main{
  background-color: black;
  color: white;
  font-size: 30px;
  font-weight: bold;
  
  .jumbotron{
    background-image: url("../assets/img/jumbotron.jpg");
    background-size: cover;
    background-repeat: no-repeat;
    height: 500px;
  }

  .container{
    width: 100%;
    height: 100%;
    padding-bottom: 20px;

    .current,
    .show{
      background-color: $primarycolor;
      padding: 10px 20px;
      text-transform: uppercase;
      font-weight: bold;
      color: white;
    }

    .container2{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    padding: 30px 0;

      img{
        width: 100%;
        height: 100%;
      }
    }

    .show{
      margin: 0px auto;
      display: block;

    }
  }
}
</style>
