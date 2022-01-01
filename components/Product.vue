<template>
  <div class="product">
    <div class="flex px-32 pt-20 pb-10">
      <img src="~/static/bg.png" class="w-full rounded-xl" data-aos="fade-up" />
    </div>
    <div class="flex px-32 pt-24 pb-36">
      <div class="w-1/2 mr-8">
        <h2 class="font-title" data-aos="fade-in">
          Accept crypto payments without processing fees and enjoy privacy by
          default.
        </h2>
      </div>
      <div class="flex flex-col font-roboto w-1/2 mt-1 ml-8">
        <p data-aos="fade-up">
          Colinear is designed to solve issues prevalent in current payment
          infastructure, including security, privacy, governance, performance,
          reliability, and high setup costs.
        </p>
        <button class="flex items-center mt-12" data-aos="fade-up">
          <div class="mr-8">GET STARTED</div>
          <img src="~/static/arrow-light.svg" />
        </button>
      </div>
    </div>
  </div>
</template>

<style scoped>
.flex {
  background: #131212;
}

h2 {
  font-size: 36px;
  line-height: 44px;
  color: #ffffff;
}

p {
  font-weight: 300;
  font-size: 20px;
  line-height: 30px;

  letter-spacing: 0.01em;
  color: #ffffff;
}

button {
  font-weight: bold;
  font-size: 21px;
  line-height: 29px;

  letter-spacing: 0.1em;
  color: #ffffff;
}
</style>