<template>
<div id='Main'>
  <Firstsection />
  <Missions />
  <Photos />
  <Love />
  <Live />
  <Jumbo2 />
  <Latest />
</div>
  
</template>

<script>
import Firstsection from './Firstsection.vue';
import Missions from './Missions.vue';
import Photos from './Photos.vue';
import Love from './Love.vue';
import Live from './Live.vue';
import Jumbo2 from './Jumbo2.vue';
import Latest from './Latest.vue';


export default {
  name: 'Main',
  components:{
      Firstsection,
      Missions,
      Photos,
      Love,
      Live,
      Jumbo2,
      Latest,
  }
}
</script>

<style scoped lang='scss'>

</style>