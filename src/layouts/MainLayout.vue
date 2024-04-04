<template>

  <div class="absolute ">
    <img src="../../public/img/nombre.png" alt="Imagen" class="relative left-1 top-40 w-86  xl:w-[33rem] xl:left-[44rem] xl:top-16 2xl:w-[34rem] 2xl:left-[62rem] 2xl:top-15" />
  </div>

<div class="w-full md:w-1/2 lg:w-1/3 xl:w-1/4 p-4 absolute lg:left-[42rem] lg:top-[1rem]  2xl:left-[56rem] 2xl:top-[4rem] ">
  <a href="https://chaturbate.com/kloelamaravilla18/" target="_blank"><img src="../../public/img/chaturbate.png" alt="Imagen" class="only absolute w-40 lg:w-52 2xl:w-72  left-[6rem]   lg:left-24 top-60 " /></a>
  <a href="https://onlyfans.com/kloe_lamaravilla18" target="_blank"> <img src="../../public/img/only.png" alt="Imagen" class="only absolute my-8  w-40 lg:w-52 2xl:w-72 left-[6rem]   lg:left-24 top-[19rem] xl:left-[23rem] xl:top-[13rem] " /></a>
</div>

<div class="flex justify-between  absolute top-[28rem] left-[1rem]  lg:left-[48rem] lg:top-[25rem] xl:top-[25rem] 2xl:top-[32rem]  2xl:left-[62rem] ">
  <div class="w-1/3 p-4">
   <a href=" https://www.tiktok.com/@_kloelamaravilla18" target="_blank"><img src="../../public/img/tiktok.png" alt="Imagen 1" class="w-20 lg:w-28 2xl:w-40" /></a>
  </div>
  <div class="w-1/3 p-4">
   <a href="https://twitter.com/oficialkloe" target="_blank"><img src="../../public/img/X.png" alt="Imagen 1" class="w-20 lg:w-28 2xl:w-40" /></a>
  </div>
  <div class="w-1/3 p-4">
   <a href="https://www.tiktok.com/@_kloelamaravilla18" target="_blank"> <img src="../../public/img/instagram.png" alt="Imagen 1" class="w-20 lg:w-28 2xl:w-40" /></a>
  </div>

  <div class="absolute top-28 left-[2.5rem] md:top-40 md:left-[5rem] 2xl:top-[12rem] 2xl:left-[5rem] flex ">
   <a href=" https://www.youtube.com/@KloeLaMaravilla/featured" target="_blank"> <img src="../../public/img/youtube.png" alt="Imagen" class="w-32 lg:w-36 2xl:w-52  " /></a>
   <a href="https://web.telegram.org/k/#@kloe_lamaravilla18" target="_blank"> <img src="../../public/img/telegram.webp" alt="Imagen" class="w-32 lg:w-36 2xl:w-52" /></a>
  </div>

</div>

<q-video
  v-if="$q.screen.gt.sm"
  src="../../public/img/Video.mp4"
  style="width: 240px; height: 430px"
  class="absolute left-[30rem] top-[10rem] 2xl:top-[20rem] 2xl:left-[32rem] "
/>



</template>

<script>
import { defineComponent, ref } from 'vue'
export default defineComponent({
  name: 'MainLayout',
})
</script>


<style scoped>


.only:hover {
  animation: shake 0.90s cubic-bezier(0.46, 0.17, 0.29, 0.97) both;
  transform: translate3d(0, 0, 0);
}

@keyframes shake {
  10%,
  90% {
    transform: translate3d(-2px, 0, 0);
  }

  20%,
  80% {
    transform: translate3d(3px, 0, 0);
  }

  30%,
  50%,
  70% {
    transform: translate3d(-5px, 0, 0);
  }

  40%,
  60% {
    transform: translate3d(5px, 0, 0);
  }
}

</style>
