<template>
  <footer>
   <Section1FooterVue/>
   <Section2FooterVue/>
  </footer>
</template>

<script>
import Section1FooterVue from '../Commons/FooterCommon/Section1Footer.vue';
import Section2FooterVue from '../Commons/FooterCommon/Section2Footer.vue';
export default {
    name: "BaseFooter",
    components: { Section1FooterVue, Section2FooterVue }
}
</script>

<style lang="scss"  scoped>

</style>