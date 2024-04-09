<template>
  <div>
    <AppTitle />
  </div>
  <div v-for="(title) in imgTitle">
    <AppMain :imgTitle="title"/>
  </div>
</template>

<script>
  import AppTitle  from './components/AppTitle.vue'
  import AppMain from './components/AppMain.vue'
  export default {
    name : 'App',
    components: {
      AppTitle,
      AppMain

    },
    data(){
      return {
        imgTitle : ['titolo1', 'titolo2']
      }
    }
  }
</script>

<style scoped>

</style>