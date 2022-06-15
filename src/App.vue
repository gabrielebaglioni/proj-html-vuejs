<template>
  <div id="app">
   <BaseHeaderVue/>
   <BaseMainVue/>
   <BaseFooterVue/>
  </div>
</template>

<script>
import BaseHeaderVue from './components/Blocks/BaseHeader.vue';
import BaseMainVue from './components/Blocks/BaseMain.vue';
import BaseFooterVue from './components/Blocks/BaseFooter.vue';


export default {
  name: 'App',
  components: {
    BaseHeaderVue,
    BaseMainVue,
    BaseFooterVue
}
}
</script>

<style lang="scss">
  @import './assets/style/global.scss'
</style>
