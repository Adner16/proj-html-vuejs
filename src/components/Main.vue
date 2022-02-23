<template>
<div id='Main'>
  <Firstsection />
  <Missions />
  <Photos />
  <Love />
  <Live />
  <Jumbo2 />
  <Latest />
  <Getstarted />
</div>
  
</template>

<script>
import Firstsection from './Firstsection';
import Missions from './Missions';
import Photos from './Photos';
import Love from './Love';
import Live from './Live';
import Jumbo2 from './Jumbo2';
import Latest from './Latest';
import Getstarted from './Getstarted';


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
      Getstarted,
  }
}
</script>

<style scoped lang='scss'>

</style>