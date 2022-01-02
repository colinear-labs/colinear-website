<template>
  <div class="product">
    <div class="flex md:flex-row flex-col xl:px-32 lg:px-12 md:px-6 px-4 lg:pt-24 md:pt-20 pt-16 lg:pb-30 md:pb-20 pb-16">
      <div class="md:w-1/2 w-full md:mr-8">
        <h2 class="font-title" data-aos="fade-in">
          Accept crypto payments without processing fees and enjoy privacy by
          default.
        </h2>
      </div>
      <div class="flex flex-col font-roboto md:w-1/2 w-full md:ml-8 md:mt-1 mt-14">
        <p data-aos="fade-up">
          Colinear is designed to solve issues prevalent in current payment
          infastructure, including security, privacy, governance, performance,
          reliability, and high setup costs.
        </p>
        <button class="flex items-center md:mt-12 mt-14" data-aos="fade-up">
          <div class="mr-8">GET STARTED</div>
          <img src="~/static/arrow-light.svg" />
        </button>
      </div>
    </div>
    <div class="md:flex hidden xl:px-32 lg:px-12 md:px-6 pb-16">
      <img src="~/static/bg.png" class="w-full rounded-md" data-aos="fade-up" />
    </div>
  </div>
</template>

<style scoped>
.product {
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