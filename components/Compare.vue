<template>
  <div class="flex md:flex-row flex-col antialiased">
    <div class="flex flex-col md:w-1/2 w-full bg-dark xl:pl-32 lg:pl-12 md:pl-8 px-4 md:pt-28 pt-16 md:pb-32 pb-20">
      <h3 class="uppercase font-roboto mb-3" data-aos="fade-in">Payments Now</h3>
      <h2 class="font-title" data-aos="fade-in">Provider-centric system</h2>
      <h4 class="font-roboto mt-10" data-aos="fade-in">Trust-based</h4>
      <div class="flex font-roboto items-center mt-8" data-aos="fade-in">
        <img src="~/static/close.svg" class="mr-4" />
        <p>Dependent on a third-party organizations.</p>
      </div>
      <div class="flex font-roboto items-center mt-7" data-aos="fade-in">
        <img src="~/static/close.svg" class="mr-4" />
        <p>Users must go through a registration process.</p>
      </div>
      <div class="flex font-roboto items-center mt-7" data-aos="fade-in">
        <img src="~/static/close.svg" class="mr-4" />
        <p>Processing providers take a fee from each payment.</p>
      </div>
      <div class="flex font-roboto items-center mt-7" data-aos="fade-in">
        <img src="~/static/close.svg" class="mr-4" />
        <p>Fully controlled by processing providers.</p>
      </div>
    </div>
    <div class="flex flex-col md:w-1/2 w-full bg-light xl:pl-32 lg:pl-12 md:pl-8 px-4 md:pt-28 pt-16 md:pb-32 pb-20">
      <h3 class="uppercase font-roboto mb-3" data-aos="fade-in">Payments With Colinear</h3>
      <h2 class="font-title" data-aos="fade-in">Merchant-centric system</h2>
      <h4 class="font-roboto mt-10" data-aos="fade-in">Decentralized</h4>
      <div class="flex font-roboto items-center mt-8" data-aos="fade-in">
        <img src="~/static/check-circle.svg" class="mr-4" />
        <p>Run by the community. Can be self-hosted.</p>
      </div>
      <div class="flex font-roboto items-center mt-7" data-aos="fade-in">
        <img src="~/static/check-circle.svg" class="mr-4" />
        <p>No business registration is required.</p>
      </div>
      <div class="flex font-roboto items-center mt-7" data-aos="fade-in">
        <img src="~/static/check-circle.svg" class="mr-4" />
        <p>No processing fees.</p>
      </div>
      <div class="flex font-roboto items-center mt-7" data-aos="fade-in">
        <img src="~/static/check-circle.svg" class="mr-4" />
        <p>Governed by its users.</p>
      </div>
    </div>
  </div>
</template>

<style scoped>
h3 {
  font-weight: 800;
  font-size: 16px;
  line-height: 22px;
  letter-spacing: 0.2em;

  color: #dedee6;
}

h2 {
  font-size: 36px;
  /* letter-spacing: 0.03em; */
  letter-spacing: -0.02em;
  color: #f0f0f7;
}

h4 {
  font-weight: 600;
  font-size: 21px;
  line-height: 25px;

  color: #dedee6;
}

p {
  font-weight: 300;
  font-size: 20px;
  line-height: 26px;

  letter-spacing: 0.02em;

  color: #f0f0f7;
}

.bg-light {
  background: #1b1a1a;
}

.bg-dark {
  background: #161515;
}
</style>