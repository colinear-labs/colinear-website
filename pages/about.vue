<template>
  <div class="about">
    <Navbar />
    <div class="flex flex-col antialiased w-5/12 pt-28 pb-40 mx-auto">
      <h2 class="font-title" data-aos="fade-up">
        We are transforming cryptocurrency into a mainstream payment method by
        building a decentralized payment processing network that allows merchants across
        the globe to accept crypto payments in a simple, secure, and private way.
      </h2>
      <h3 class="font-roboto uppercase mt-16 mb-4" data-aos="fade-up">
        Technology
      </h3>
      <p class="font-roboto" data-aos="fade-up">
        Colinear's network consists of payments servers (which can be run by
        trusted community members or merchants themselves) and full nodes (which are run by
        node operators). Payment servers generate payment intents on behalf of merchants, and 
        send them to full nodes, which then scan the relevant blockchains to ensure that the 
        user transactions are properly submitted to the mempool and confirmed on-chain. Full nodes
        then inform the payment servers when (or if) the intents have been completed, and the servers 
        can emit a webhook to any API endpoint of the merchant's choosing.
      </p>
      <h3 class="font-roboto uppercase mt-16 mb-4" data-aos="fade-in">
        ECOSYSTEM
      </h3>
      <p class="font-roboto" data-aos="fade-in">
        Node operators are rewarded for processing payments through the minting of a 
        governance token (CLR), which can be used for protocol governance votes. If 
        the operators would not like to participate, they are able to simply liquidate 
        their CLR tokens on an exchange so that others can buy them and participate. 
        As CLR will have a set inflation rate to reward operators, protocol votes will 
        burn CLR to keep the token supply in relative equilibrium.
      </p>

      <!-- Add team section back in later -->

      <!-- <h3 class="font-roboto uppercase mt-16 mb-4" data-aos="fade-in">TEAM</h3>
      <p class="font-roboto" data-aos="fade-in">
        The team donec ac odio tempor orci. Vel fringilla est ullamcorper eget
        nulla facilisi. Viverra suspendisse potenti nullam ac tortor vitae.
        Pulvinar etiam non quam lacus suspendisse faucibus. Tristique risus nec
        feugiat in fermentum posuere urna nec tincidunt.
        <br />
        <br />
        The Colinear ecosystem vel pharetra vel turpis. Tortor condimentum
        lacinia quis vel. Pharetra convallis posuere morbi leo urna molestie at.
        Pellentesque elit eget gravida cum sociis natoque. Enim blandit volutpat
        maecenas volutpat. Posuere morbi leo urna molestie. Id semper risus in
        hendrerit gravida rutrum quisque non tellus.
      </p> -->
    </div>
    <Footer />
  </div>
</template>

<style scoped>
h2 {
  font-size: 29px;
  line-height: 36px;
  letter-spacing: 0.01em;

  color: rgb(5, 5, 5);
}

h3 {
  font-size: 16px;
  line-height: 36px;

  letter-spacing: 0.25em;

  color: #7e7e81;
}

p {
  font-size: 18px;
  line-height: 29px;
  letter-spacing: -0.01em;
  color: rgb(5, 5, 5);
}

.about {
  background: #f0f0f6;
}
</style>