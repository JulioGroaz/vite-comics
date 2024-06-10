<script>
import ComicsHeader from './components/ComicsHeader.vue';
import ComicsMain from './components/ComicsMain.vue';
import ComicsFooter from './components/ComicsFooter.vue';



export default{
  data(){
    return{

    }
  },
  components:{
    ComicsHeader,
    ComicsMain,
    ComicsFooter
  }
}
</script>

<template>

  <ComicsHeader/>

  <ComicsMain/>

  <ComicsFooter/>

</template>

<style>


</style>
