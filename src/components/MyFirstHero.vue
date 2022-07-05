<template>
  <div class="jumbotron">
    <div class="am-img-cover">
      <img src="../assets/tec.jpg" alt="Programmazione">
    </div>       
  </div>
</template>

<script>
export default {
  name: 'MyFirstHero',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
img {
  width: 100%;
  height: 400px;
  object-fit: cover;
}

</style>
