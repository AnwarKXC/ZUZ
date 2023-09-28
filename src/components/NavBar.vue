<template>
   <header class=" relative w-screen md:h-[500px]  overflow-hidden ">
      <nav 
         class="bg-black w-screen h-28 text-white flex list-none md:gap-8 gap-4 items-center sticky z-10 md:justify-end justify-center md:px-24 font-medium px-2  ">
         <li><a href="">HOME</a></li>
         <li><a href="">ABOUT</a></li>
         <li><a href="">CONTRACT</a></li>
         <button class=" bg-red-700 py-2 px-3 rounded  -tracking-wide"><a href="">SIGN UP</a>
         </button>
         <div class="bg-black w-screen  h-[410px] absolute -top-24 right-0  skew-y-[-12deg] -z-50">
         </div>
      </nav>
      <h1
         class="text-white font-bold text-3xl lg:text-6xl absolute top-32 lg:top-20 tracking-wide lg:leading-[60px] leading-[46px] z-10 md:left-24 left-[calc(5%)]">
         FIGHT LIKE A <br>
         <span class=" text-red-600">CHAMPION</span>
      </h1>
      <div class="  z-20  lg:-top-52 -top-36 relative lg:left-[calc(30%)] lg:w-[calc(40%)] mx-4">
         <div class="left-[calc(85%-196px)] lg:left-[calc(70%-196px)] lg:top-[105px] relative xl:w-96 w-80 xl:left-[calc(50%-196px)] xl:top-10  top-14 " >
            <img src="/public/05b8ff275ddaafa20e243c159c3114a4-removebg-preview.png" alt="">
         </div>
         <div
            class=" md:min-w-[600px] bg-[#e6e6e6] md:top-[360px] top-[330px] z-30 absolute rounded-xl w-full md:h-24  py-1 drop-shadow-2xl shadow flex justify-around  items-center text-red-700 font-semibold md:text-[22px] ">

            <div class="flex flex-col justify-center items-center">
               <span class="material-symbols-outlined text-black md:text-[52px] text-[36px]">
                  sports_martial_arts
               </span>
               CROSSFIT
            </div>
            <div class="flex flex-col justify-center items-center">
               <span class="material-symbols-outlined text-black md:text-[52px] text-[36px]">
                  fitness_center
               </span>
               WEIGHTS
            </div>
            <div class="flex flex-col justify-center items-center">
               <span class="material-symbols-outlined text-black md:text-[52px] text-[36px]">
                  heart_plus
               </span>
               EXCERCISE
            </div>
         </div>
      </div>
   </header>
</template>

<script setup lang="ts">

</script>

<style scoped></style>