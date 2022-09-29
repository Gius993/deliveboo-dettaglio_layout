<template>
  <div id="app">
    <div class="my_class">

      <PageUtent />
    </div>
    <MainComponent />
  </div>
</template>

<script>

import PageUtent from './components/PageUtent.vue';
import MainComponent from './components/MainComponent.vue';

export default {
  name: 'App',
  components: {
    PageUtent,
    MainComponent
}
}
</script>

<style lang="scss">
 @import url('https://fonts.googleapis.com/css2?family=IBM+Plex+Sans:wght@300;400;500;700&family=Pacifico&display=swap');

  *{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    img{
      width: 100%;
    }
    a{
      text-decoration: none;
      color: inherit;
    }
  }
  body{
    font-family: 'IBM Plex Sans', 
    sans-serif;
  }
  .my_class{
    display: none;
  }
</style>
