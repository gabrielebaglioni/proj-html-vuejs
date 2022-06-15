<template>
  <div class="background text-white">
       <div class="w-full flex justify-center items-center pt-20 text-center ">
         <div>
            <h2 class="font-bold text-2xl mb-6" > CHANGE A LIFE TODAY </h2>
            <div class="w-full flex justify-center">
                <hr class="w-96 border-yellow-600  mb-6">
            </div>
            <h5> Lorem, ipsum dolor sit amet consectetur adipisicing elit. Quo voluptates repudiandae <br>Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime sunt  </h5>
            <div class="py-16">
               <button class="bt-white px-2 py-1 mr-5 ">VOLUTEER</button>
               <button class="bt-white px-2 py-1 ml-5 ">DONATE NOW</button>
            </div>
            
         </div>
               
      </div>
  </div>
</template>

<script>
export default {
  name: 'Section5Main'
}
</script>

<style lang="scss" scoped>
 .background{
   background-image: url(../../../assets/images/home-footer.jpg);
   background-size: cover;
   
   
 }
 .bt-white{
  border: 1px solid white;
}
</style>