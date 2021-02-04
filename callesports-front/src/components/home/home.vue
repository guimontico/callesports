<template lang="html">
  <section class="home">
    <topbarmenu />
    <h1>home Components</h1>
    <footerComponent />
  </section>

</template>

<script lang="js">
  import topbarmenu from '../shared/topbarmenu.vue'
  //eslint-disable-next-line no-unused-vars
  import footerComponent from '../footer/footer-component.vue'

  export default  {
    name: 'home',
    components:{
      topbarmenu,
      footerComponent
    },
    props: [],
    mounted () {

    },
    data () {
      return {

      }
    },
    methods: {

    },
    computed: {

    }
}


</script>

<style scoped lang="scss">
  .home {
    padding: 0;
    margin: 0;
  }
  body {    
    margin: 0 !important;
    padding: 0 !important;
  }
</style>
