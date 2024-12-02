
<template>


    <!-- <section class="max-w-screen-sm flex flex-col mx-auto p-8 pt-8 ">
      <div class="grid grid-cols-3 grid-rows-3 gap-2 md:gap-3">
        <div class="h-16 md:h-32 bg-gray-400 rounded-lg"></div>
        <div class="bg-gray-400 row-span-2 rounded-lg"></div>
        <div class="bg-gray-400 rounded-lg"></div>
        <div class="bg-gray-400 row-span-2 rounded-lg"></div>
        <div class="bg-gray-400 row-span-2 rounded-lg"></div>
        <div class="bg-gray-400 rounded-lg"></div>
      </div>
      <p class="text-gray-500 pt-3 text-xs md:text-sm"># Interdependent harmonic oscillation. An abstract phenomenon commonly observed in many distinct areas of nature in many different forms, as if by design.</p>
    </section> -->


    <!-- <section class="max-w-screen-sm flex flex-col mx-auto p-8 pt-8 "> -->
    <!--   <p class="text-gray-200 font-bold">Published Articles</p> -->
    <!--   <div class="bg-gray-300 text-xs md:text-sm text-gray-900 m-2 p-2 border rounded"> -->
    <!--     No articles published yet. -->
    <!--   </div> -->
    <!-- </section> -->

</template>


<style scoped>
/* Keyframes for scaling animation */
@keyframes scalePulse {
  0%, 100% {
    transform: scale(1);
  }
  50% {
    transform: scale(1.1);
  }
}

/* Keyframes for subtle move */
@keyframes subtleMove {
  0%, 100% {
    transform: translate(0, 0);
  }
  25% {
    transform: translate(-5px, -5px);
  }
  50% {
    transform: translate(5px, 5px);
  }
  75% {
    transform: translate(-5px, 5px);
  }
}

/* General grid animation */
.grid div {
  animation: scalePulse 6s infinite ease-in-out, subtleMove 8s infinite ease-in-out;
  will-change: transform;
}

/* Individual delay for each grid cell to create staggered effect */
.grid div:nth-child(1) { animation-delay: 0s, -0.5s; }
.grid div:nth-child(2) { animation-delay: 0.1s, -0.6s; }
.grid div:nth-child(3) { animation-delay: 0.2s, -0.7s; }
.grid div:nth-child(4) { animation-delay: 0.3s, -0.8s; }
.grid div:nth-child(5) { animation-delay: 0.4s, -0.9s; }
.grid div:nth-child(6) { animation-delay: 0.5s, -1s; }


</style>


