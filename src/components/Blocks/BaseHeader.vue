<template>
   <header>
      <div class="background">
        <h1>Some text</h1>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Quaerat dolor fugiat nostrum quibusdam eius molestiae rerum laboriosam voluptatum magnam quis alias asperiores totam animi perferendis fuga id officia, cupiditate quod.</p>
        <NavbarHeaderVue/>
        <WelcomeHeaderVue/>
      </div>
   </header>
</template>

<script>
import NavbarHeaderVue from "../Commons/HeaderCommon/NavbarHeader.vue";
import WelcomeHeaderVue from "../Commons/HeaderCommon/WelcomeHeader.vue";


export default {
    name: "BaseHeader",
    components: { NavbarHeaderVue, WelcomeHeaderVue }
}
</script>

<style lang="scss" scoped>
.background{
  color: white;
  background-image: url(../../assets/images/home-page-slider.jpg);
}

   
</style>