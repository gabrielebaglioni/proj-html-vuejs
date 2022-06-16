<template>
  <nav class="w-full flex justify-between p-4 items-center">
    <div class=" flex justify-start items-center">
       <img src="../../../assets/images/avada-charity-logo.png" alt="" class="w-37 cursor-pointer">
    </div>
    <ul class="flex list-none flex-row justify-between items-center flex-initial cursor-pointer ">
      <li v-for="(link, index) in links" :key="index" @click="getActive(index)">
         <a :class="{ active : link.active}">{{link.text}}</a>
      </li>
      <!-- <li><a href="#"></a>Mission</li>
      <li><a href="#"></a>Causes</li>
      <li><a href="#"></a>Jurnal</li> -->
       <button class=' py-2 px-7 mx-4  cursor-pointer bg-amber-500 hover:bg-amber-600'>
            login
       </button>
    </ul>
  </nav>
</template>

<script>
export default {
   name: 'NavbarHeader',
        data() {
      return{
        links :[
          {
            text: 'HOME',
            href: '#',
            active: true,
          },
           {
            text: 'MISSION',
            href: '#',
            active: false,
          },
           {
            text: 'CAUSES',
            href: '#',
            active: false,
          },
           {
            text: 'JURNAL',
            href: '#',
            active: false,
          },
        ]
      }
    },
    methods:{
      getActive(index){
        this.links.forEach((link) => link.active = false );
        this.links[index].active = !this.links[index].active;
      }
    },
}
</script>

<style lang="scss" scoped>
 li{
  margin: 0 20px;
 }
 .active{
   color: rgb(209, 165, 6);
 }

</style>