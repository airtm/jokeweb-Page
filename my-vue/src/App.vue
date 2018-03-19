<template>
  <div id="app22">
   <!-- <img src="./assets/logo.png"> -->
   笑话精选

   <div class="loading">
   <img src="./assets/o_zoro.gif" />
   <span>永不停歇，向上人生路！</span>
   </div>


<router-view/>
  </div>
</template>


<script>
export default {
  name: 'App1'
}

</script>

<style>
#app22 {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
/* .loading img {
  margin-top: 100px;
  margin-left: 1100px;
      opacity: 0;
} */
.loading {
  position: fixed;
  top: 200px;
  left: 1300px;
  z-index: 999;
  height: 50%;
  width: 600px;
  text-align: center;
  background: #ffffff;
  font-size: 18px;
  visibility: hidden;
  opacity: 0;
  -webkit-animation: loading 3s linear; /**此处是3秒消失，可根据自行需要调整时间**/
}
@-webkit-keyframes loading {
  0%{opacity: 1;visibility: visible;}
  90%{opacity: 1;}
  100%{opacity: 0;visibility: visible;}
}
</style>
