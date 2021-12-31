<template>
  <div class="flex antialiased">
    <div class="flex flex-col w-1/2 bg-dark pl-32 pt-28 pb-32">
      <h3 class="uppercase font-roboto mb-3" data-aos="fade-in">Payments Now</h3>
      <h2 class="font-title" data-aos="fade-in">Provider-centric system</h2>
      <h4 class="font-roboto mt-10" data-aos="fade-in">Trust-based</h4>
      <div class="flex font-roboto items-center mt-8" data-aos="fade-in">
        <img src="~/static/close.svg" class="mr-4" />
        <p>Data Security is third-party dependent.</p>
      </div>
      <div class="flex font-roboto items-center mt-7" data-aos="fade-in">
        <img src="~/static/close.svg" class="mr-4" />
        <p>No Privacy.</p>
      </div>
      <div class="flex font-roboto items-center mt-7" data-aos="fade-in">
        <img src="~/static/close.svg" class="mr-4" />
        <p>High-fees, not optimal performance.</p>
      </div>
      <div class="flex font-roboto items-center mt-7" data-aos="fade-in">
        <img src="~/static/close.svg" class="mr-4" />
        <p>Controlled by payment providers solely.</p>
      </div>
    </div>
    <div class="flex flex-col w-1/2 bg-light px-32 py-28">
      <h3 class="uppercase font-roboto mb-3" data-aos="fade-in">Payments With Colinear</h3>
      <h2 class="font-title" data-aos="fade-in">Merchant-centric system</h2>
      <h4 class="font-roboto mt-10" data-aos="fade-in">Decentralized</h4>
      <div class="flex font-roboto items-center mt-8" data-aos="fade-in">
        <img src="~/static/check-circle.svg" class="mr-4" />
        <p>True End-to-End Data Security.</p>
      </div>
      <div class="flex font-roboto items-center mt-7" data-aos="fade-in">
        <img src="~/static/check-circle.svg" class="mr-4" />
        <p>Privacy by default.</p>
      </div>
      <div class="flex font-roboto items-center mt-7" data-aos="fade-in">
        <img src="~/static/check-circle.svg" class="mr-4" />
        <p>Best possible performance.</p>
      </div>
      <div class="flex font-roboto items-center mt-7" data-aos="fade-in">
        <img src="~/static/check-circle.svg" class="mr-4" />
        <p>Governed by its Users.</p>
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
  letter-spacing: 0.03em;
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