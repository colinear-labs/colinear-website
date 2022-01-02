<template>
  <div class="flex md:flex-row flex-col xl:px-32 lg:px-12 md:px-6 px-4 lg:pt-36 md:pt-24 pt-16 md:pb-40 pb-16">
    <div class="md:w-1/2 w-full md:mr-8">
      <h2 class="font-title" data-aos="fade-in">
        Colinear is a decentralized payment gateway powering the next generation
        of global commerce.
      </h2>
    </div>
    <div class="flex flex-col font-roboto md:w-1/2 w-full md:ml-8 md:mt-0 mt-16">
      <p data-aos="fade-up">
        Colinear is designed to solve issues prevalent in current payment
        infastructure, including security, privacy, governance, performance,
        reliability, and high setup costs.
        <br />
        <br />
        It is based on a peer to peer (P2P) network that includes blockchain
        nodes, proof of stake, encrypted routing, and an economic model that
        enables and fosters the deployment of this architecture.
      </p>
      <button class="flex items-center md:mt-12 mt-14" data-aos="fade-up">
        <div class="mr-8">ABOUT</div>
        <img src="~/static/arrow.svg" />
      </button>
    </div>
  </div>
</template>

<style scoped>
h2 {
  font-size: 36px;
  line-height: 44px;
}

p {
  font-weight: 300;
  font-size: 20px;
  line-height: 30px;

  letter-spacing: 0.01em;
}

.flex {
  /* background: #f7f7fc; */
  background: #f0f0f6;
}

button {
  font-weight: bold;
  font-size: 21px;
  line-height: 29px;

  letter-spacing: 0.1em;
}
</style>