<template>
  <main>
     <Section1MainVue/>
     <Section2MainVue/>
     <Section3MainVue/>
     <SeparatorMainVue/>
  </main>
</template>

<script>
import Section1MainVue from '../Commons/MainCommons/Section1Main.vue';
import Section2MainVue from '../Commons/MainCommons/Section2Main.vue';
import Section3MainVue from '../Commons/MainCommons/Section3Main.vue';
import SeparatorMainVue from '../Commons/MainCommons/SeparatorMain.vue';




export default {
    name: "BaseMain",
    components: { Section1MainVue, Section2MainVue, Section3MainVue, SeparatorMainVue }
}
</script>

<style lang="scss" scoped>

</style>