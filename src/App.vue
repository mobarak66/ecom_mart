<template>
  <HeaderView/>
  <router-view/>
  <FooterView/>
</template>
<script>
 import HeaderView from './components/includes/HeaderView.vue';
 import FooterView from './components/includes/FooterView.vue';
  export default{
    name: "App",
    components: {HeaderView,FooterView}
  }
</script>

<style>

</style>
