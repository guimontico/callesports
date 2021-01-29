<template lang="html">
  <section class="home">
    <topbarmenu />
    <h1>home Components</h1>
  </section>

</template>

<script lang="js">
  import topbarmenu from '../shared/topbarmenu.vue'

  export default  {
    name: 'home',
    components:{
      topbarmenu
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
