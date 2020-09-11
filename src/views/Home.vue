<template>
  <div class="home">
    <router-link to="/Like" class="route">关注</router-link>
    <router-link to="/Faxian" class="route">发现</router-link>
    <router-link to="/City" class="route">同城</router-link>
    <br/>
    <img src="../img/1.jpg" class="img"/>
    <img src="../img/2.jpg" class="img"/>
    <img src="../img/3.jpg" class="img"/>
    <img src="../img/4.jpg" class="img"/>
  </div>
</template>

<script>
export default {};
</script>

<style>
.home{
  width: 100%;
  height: 100%;
}
.route {
  float: left;
  margin-right: 10px;
  text-decoration: none;
  color: black;
  font-size: 30px;
  text-align: center;
}
.route.active {
  color: red;
}
img{
  width: 50%;
  float: left;
}
</style>