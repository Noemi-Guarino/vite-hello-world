
<script>
// importazione componente apptitle

import AppTitle from './components/AppTitle.vue';
export default {
  data() {
    return { 

    }
  },
  // dichiarazione del componente all'interno dell'ogettoù
  components:{
    AppTitle
  }
};
</script>

<template>
  <div>
    <!-- utilizzo del componente -->
    <AppTitle/>
  </div>
</template>

<style scoped>
</style>
