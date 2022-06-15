<template>
  <div class="w-full flex">
     <div class="w-2/3">
      <div class="flex flex-col items-start py-12 px-20 max-w-6xl">
         <h2 class="mb-3 text-2xl">EVERY MOMENTS COUNT</h2>
         <hr class="w-32 border-yellow-600 mb-3">
         <p class="my-3">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Non optio labore at, veniam itaque mollitia aspernatur error obcaecati nam similique ut distinctio? Odio, quisquam? Amet esse dicta pariatur architecto rem.</p>
         <p class="my-3">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Atque, sit! Vel asperiores atque odio, totam consequuntur blanditiis sapiente in unde, fuga cumque obcaecati praesentium et velit dicta voluptate harum suscipit.</p>
         <p class="my-3">Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam corporis, facere reiciendis recusandae tenetur </p>
         <button class=' py-2 px-7  cursor-pointer bg-amber-500 text-white '>
            Our Mission
         </button>
         <span><i class="fa-solid fa-heart"></i></span>
      </div>
     </div>
     <div class="w-1/3 background">
       <div class="flex flex-col justify-center items-center pt-20 text-white">
          <span class="text-center font-extrabold">2032</span>
          <p class="mb-8">voluntaries worldwild</p>
          <span class="text-center font-extrabold">132</span>
          <p class="mb-8">Active project</p>
          <span class="text-center font-extrabold">$ 1.5 M</span>
          <p>Donate</p>
       </div>
     </div>
  </div>
</template>

<script>
export default {
 name: 'Section1Main'
}
</script>

<style lang="scss" scoped>
.background{
   background-image: url(../../../assets/images/home-content-bg-1.jpg);
   background-size: contain;
   background-size: cover;
}

</style>