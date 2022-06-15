<template>
  <nav class="w-full flex justify-between p-4 items-center">
    <div class=" flex justify-start items-center">
       <img src="../../../assets/images/avada-charity-logo.png" alt="" class="w-37 cursor-pointer">
    </div>
    <ul class="flex list-none flex-row justify-between items-center flex-initial  ">
      <li><a href="#"></a>Home</li>
      <li><a href="#"></a>Mission</li>
      <li><a href="#"></a>Causes</li>
      <li><a href="#"></a>Jurnal</li>
       <li class=' py-2 px-7 mx-4  cursor-pointer bg-amber-500 '>
            login
       </li>
    </ul>
  </nav>
</template>

<script>
export default {
   name: 'NavbarHeader'
}
</script>

<style lang="scss" scoped>
 li{
  margin: 0 20px;
 }

</style>