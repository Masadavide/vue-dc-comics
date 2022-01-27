<template>
  <header>
    <div class="container">
      <div class="logo">
        <img src="../assets/img/dc-logo.png" alt="">
      </div>
      <div class="menu">
        <ul>
          <li>
            <a href="#">
              Characters
            </a>
          </li>
          <li class="active">
            <a href="#">
              Comics
            </a>
          </li>
          <li>
            <a href="#">
              Movies
            </a>
          </li>
          <li>
            <a href="#">
              Tv
            </a>
          </li>
          <li>
            <a href="#">
              Games
            </a>
          </li>
          <li>
            <a href="#">
              Collectibles
            </a>
          </li>
          <li>
            <a href="#">
              Video
            </a>
          </li>
          <li>
            <a href="#">
              Fans
            </a>
          </li>
          <li>
            <a href="#">
              News
            </a>
          </li>
          <li>
            <a href="#">
              Shop
            </a>
          </li>
        </ul>
      </div>
    </div>
  </header>
</template>

<script>
export default {
  name: 'Header'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">

.container{
  display: flex;
  justify-content: space-between;
  align-items: center;
}

li{
  text-transform: uppercase;
  list-style: none;
  font-weight: bold;
  display: inline-block;
  padding: 10px;

  a{
    text-decoration: none;
    color: black;
  }
}
</style>
