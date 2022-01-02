<template>
  <div class="flex md:flex-row flex-col xl:px-32 lg:px-12 md:px-6 px-4 lg:py-32 md:py-24 py-16">
    <div class="flex flex-col md:w-1/2 w-full">
      <h2 class="font-title" data-aos="fade-in">
        Colinear Network Token (CLR) secures our Proof-of-Stake network.
      </h2>
      <button class="md:flex hidden items-center mt-24" data-aos="fade-in">
        <div class="mr-12">MORE ABOUT CLR</div>
        <img src="~/static/arrow-light.svg"/>
      </button>
    </div>
    <div class="flex flex-col font-roboto md:w-1/3 w-full md:ml-32 md:mt-0 mt-16" data-aos="fade-in">
      <p class="mb-8"><b class="font-bold">Ensuring valid</b> <span class="text-gray-300">payment confirmations sent to merchant servers.</span></p>
      <p class="mb-8"><b class="font-bold">Unlocking secure</b> <span class="text-gray-300">and fast payments between two peers.</span></p>
      <p><b class="font-bold">Governing the network</b> <span class="text-gray-300">to enable democratized developement.</span></p>
    </div>
    <button class="md:hidden flex items-center mt-20" data-aos="fade-in">
      <div class="mr-12">MORE ABOUT CLR</div>
      <img src="~/static/arrow-light.svg"/>
    </button>
  </div>
</template>

<style scoped>
h2 {
  font-style: normal;
  font-weight: 600;
  font-size: 29px;
  line-height: 36px;

  color: #f7f7fe;
}

button {
  font-style: normal;
  font-weight: bold;
  font-size: 21px;
  line-height: 29px;

  letter-spacing: 0.1em;

  color: #ffffff;
}

p {
  font-style: normal;
  font-weight: 300;
  font-size: 19px;
  line-height: 26px;

  letter-spacing: 0.03em;

  color: #f7f7fe;
}

.flex {
  background: #131212;
}
</style>