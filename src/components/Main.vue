<template>
  <main>
    <div class="container">
      <div>
        --> Content goes here  &#60;--
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: 'Main'
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import '../assets/style/partial/variables.scss';
main{
  background-color: black;
  color: white;
  font-size: 30px;
  font-weight: bold;

  .container{
  display: flex;
  align-items: center;
}
}
</style>
