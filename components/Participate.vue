<template>
  <div class="flex flex-col xl:px-32 lg:px-12 md:px-6 px-4 lg:py-32 md:py-24 py-16">
    <h2 class="font-title subpixel-antialiased" data-aos="fade-in">
      Network users can participate <br class="md:block hidden"/>
      in Colinear by becoming:
    </h2>
    <div class="flex md:flex-row flex-col font-roboto justify-between mt-16" data-aos="fade-in">
      <p class="md:mr-10 md:mb-0 mb-10">
        <b class="font-semibold">Full nodes</b> - share and monetize their
        blockchain nodes.
      </p>
      <p class="md:mr-10 md:mb-0 mb-10">
        <b class="font-semibold">Validators</b> - validate and audit full
        node operators.
      </p>
      <p>
        <b class="font-semibold">End Users</b> - integrate Colinear
        and accept cryptocurrency payments.
      </p>
    </div>
    <button class="flex items-center mt-16" data-aos="fade-in">
      <div class="mr-8">START STAKING</div>
      <img src="~/static/arrow.svg" />
    </button>
  </div>
</template>

<style scoped>
h2 {
  font-weight: 600;
  font-size: 29px;
  line-height: 36px;

  color: #161515;
}

p {
  font-style: normal;
  font-size: 19px;
  line-height: 26px;

  letter-spacing: 0.01em;

  color: #161515;
}

button {
  font-weight: bold;
  font-size: 21px;
  line-height: 29px;

  letter-spacing: 0.1em;

  color: #000000;
}

.flex {
  background: #f0f0f6;
}
</style>