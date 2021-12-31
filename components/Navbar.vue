<template>
  <div class="flex pl-32 pr-24 pt-12 antialiased">
    <nuxt-link to="/" class="mr-auto" style="height: 38px;" >
      <img src="~/static/logo_v3.svg" class="mr-auto" style="margin-left: -5px;" />
    </nuxt-link>
    <div class="flex items-center">
      <nuxt-link to="/" class="mr-10"> Home </nuxt-link>
      <nuxt-link to="/about" class="mr-10"> About </nuxt-link>
      <nuxt-link to="/staking" class="mr-10"> Staking </nuxt-link>
      <nuxt-link to="/faq" class="mr-10"> F.A.Q </nuxt-link>
      <nuxt-link to="/news" class="mr-10"> News </nuxt-link>
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

a.nuxt-link-exact-active {
  text-decoration: underline;
  text-underline-offset: 5px;
}
</style>