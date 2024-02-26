<script lang="ts">
  import Banner from './components/Banner.vue';
  import ConteudoPrincipal from './components/ConteudoPrincipal.vue';

  export default {
    components: {
      Banner,
      ConteudoPrincipal
    }
  }
</script>

<template>
  <div>
    <Banner />
    <ConteudoPrincipal />
  </div>
</template>