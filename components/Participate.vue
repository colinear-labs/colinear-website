<template>
  <div class="flex flex-col px-32 py-36">
    <h2 class="font-roboto" data-aos="fade-in">
      Network users can participate <br />
      in Colinear by becoming:
    </h2>
    <div class="flex font-roboto justify-between mt-16" data-aos="fade-in">
      <p class="mr-10">
        <b class="font-semibold">Full nodes</b> - share and monetize their
        compute resources.
      </p>
      <p class="mr-10">
        <b class="font-semibold">Validators</b> - validate and audit payment
        node opperators.
      </p>
      <p>
        <b class="font-semibold">End Users</b> - integrate Colinear
        and accept cryptocurrency payments.
      </p>
    </div>
    <button class="flex items-center mt-16" data-aos="fade-in">
      <div class="mr-8">START STAKING NOW</div>
      <img src="~/static/arrow.svg" />
    </button>
  </div>
</template>

<style scoped>
h2 {
  font-style: normal;
  font-weight: 600;
  font-size: 28px;
  line-height: 36px;

  color: #161515;
}

p {
  font-style: normal;
  font-weight: 300;
  font-size: 19px;
  line-height: 26px;

  letter-spacing: 0.02em;

  color: #161515;
}

button {
  font-style: normal;
  font-weight: bold;
  font-size: 21px;
  line-height: 26px;

  letter-spacing: 0.1em;

  color: #000000;
}

.flex {
  background: #f0f0f6;
}
</style>