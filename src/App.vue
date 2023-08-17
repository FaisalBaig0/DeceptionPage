<template>
  <div>
  <HeaderCom/>
  <BodyCom/>

  
  </div>
<FooterCom/>

</template>
<script>
import HeaderCom from './components/HeaderCom.vue';
import FooterCom from './components/FooterCom.vue';
import BodyCom from './components/BodyCom.vue';
export default {
  name:'App',
  components:{
    FooterCom,
    HeaderCom,
    BodyCom
  }
}
</script>
<style>
#app {
  font-family: 'Times New Roman', Times, serif, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}


</style>
