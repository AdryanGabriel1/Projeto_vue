<!--caixa de imports e exports-->
<!--define 'App.Vue' como "pai" e os imports de 'components como "filhos"-->
<script lang="ts">

import Banner from './components/Banner.vue';
import ConteudoPrincipal from './components/ConteudoPrincipal.vue';

export default{
  components: {Banner, ConteudoPrincipal}
}

</script>


<template> 

  <Banner/>
  <ConteudoPrincipal/>

</template>
