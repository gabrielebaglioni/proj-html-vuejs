<template>
  <main>
     <Section1MainVue/>
     <Section2MainVue/>
  </main>
</template>

<script>
import Section1MainVue from '../Commons/MainCommons/Section1Main.vue';
import Section2MainVue from '../Commons/MainCommons/Section2Main.vue';


export default {
    name: "BaseMain",
    components: { Section1MainVue, Section2MainVue }
}
</script>

<style lang="scss" scoped>

</style>