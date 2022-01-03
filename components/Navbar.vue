<template>
  <div class="flex xl:pl-32 xl:pr-24 lg:pl-12 lg:pr-8 md:px-6 px-4 lg:pt-12 md:pt-10 pt-6 antialiased">
    <nuxt-link to="/" class="mr-auto" style="height: 38px;" >
      <img src="~/static/logo_v3.svg" class="mr-auto" style="margin-left: -5px;" />
    </nuxt-link>
    <div class="lg:flex items-center hidden">
      <nuxt-link to="/" class="mr-10"> Home </nuxt-link>
      <nuxt-link to="/about" class="mr-10"> About </nuxt-link>
      <a class="mr-10" href="https://github.com/colinear-labs" target="_blank">Github</a>
      <!-- <a class="mr-10" href="https://www.twitter.com" target="_blank"> Twitter </a> -->
      <!-- <nuxt-link to="/faq" class="mr-10"> F.A.Q </nuxt-link> -->
      <!-- <nuxt-link to="/news" class="mr-10"> News </nuxt-link> -->
      <a href="https://docs.colinear.io" target="_blank" class="mr-10"> Documentation &nbsp;&#8599; </a>
    </div>
  </div>
</template>

<style scoped>
.flex {
  background: #f0f0f6;
}

a {
  font-style: normal;
  font-weight: normal;
  font-size: 17px;
  line-height: 21px;

  letter-spacing: 0.01em;

  color: #000000;
}

a:hover {
  color: #7c7c7c;
}
</style>