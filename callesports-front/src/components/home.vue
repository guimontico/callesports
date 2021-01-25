<template lang="html">
  <section class="home">
    <topbarmenu />
    <h1>home Components</h1>
  </section>

</template>

<script lang="js">
  import topbarmenu from './topbarmenu'

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

  }
</style>
