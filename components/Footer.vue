<template>
  <div
    class="
      flex flex-col
      antialiased
      xl:px-32
      lg:px-12
      md:px-6
      px-4
      lg:pt-28
      md:pt-24
      pt-16
      pb-12
    "
  >
    <div class="flex md:flex-row flex-col justify-between">
      <div class="flex flex-col md:w-1/3 w-full">
        <h2 class="font-roboto" data-aos="fade-in">
          Start building with <br class="lg:block md:hidden block"/>
          Colinear today.
        </h2>
        <button
          class="
            md:flex
            hidden
            items-center
            mt-auto
            text-white
            border border-gray-200
            rounded
            w-48
            px-5
            py-3
            mb-1
          "
        >
          <div>Documentation</div>
          <img src="~/static/arrow-up-right.svg" class="ml-auto" />
        </button>
      </div>
      <div class="flex flex-col md:w-1/4 w-full md:mt-1 mt-12">
        <h3 class="md:mb-8 mb-5" data-aos="fade-in">Quick start</h3>
        <a class="flex justify-between items-center mb-4" data-aos="fade-in">
          <p>What is Colinear network?</p>
          <img src="~/static/arrow-up-right.svg" />
        </a>
        <a class="flex justify-between items-center mb-4" data-aos="fade-in">
          <p>What is Colinear CLI?</p>
          <img src="~/static/arrow-up-right.svg" />
        </a>
        <a class="flex justify-between items-center mb-4" data-aos="fade-in">
          <p>Get started with Colinear CLI</p>
          <img src="~/static/arrow-up-right.svg" />
        </a>
        <a class="flex justify-between items-center mb-4" data-aos="fade-in">
          <p>Install Colinear Gateway</p>
          <img src="~/static/arrow-up-right.svg" />
        </a>
        <a class="flex justify-between items-center" data-aos="fade-in">
          <p>Create a Node</p>
          <img src="~/static/arrow-up-right.svg" />
        </a>
      </div>
      <div class="flex flex-col lg:w-1/5 md:w-1/4 w-full md:mt-1 mt-12">
        <h3 class="md:mb-8 mb-5" data-aos="fade-in">Community</h3>
        <a class="flex justify-between items-center mb-4" data-aos="fade-in">
          <p>Github</p>
          <img src="~/static/arrow-up-right.svg" />
        </a>
        <a class="flex justify-between items-center mb-4" data-aos="fade-in">
          <p>Dockerhub</p>
          <img src="~/static/arrow-up-right.svg" />
        </a>
        <a class="flex justify-between items-center mb-4" data-aos="fade-in">
          <p>PyPI</p>
          <img src="~/static/arrow-up-right.svg" />
        </a>
        <a class="flex justify-between items-center" data-aos="fade-in">
          <p>Twitter</p>
          <img src="~/static/arrow-up-right.svg" />
        </a>
      </div>
    </div>
    <button
      class="
        md:hidden
        flex
        items-center
        text-white
        border border-gray-200
        rounded
        w-full
        px-5
        py-3
        my-10
      "
    >
      <div>Developer Documentation</div>
      <img src="~/static/arrow-up-right.svg" class="ml-auto" />
    </button>
    <hr class="border-t border-neutral-700 md:mt-20 mb-12" />
    <div class="flex justify-between items-center">
      <small class="text-sm text-gray-100"
        >Copyright © {{ new Date().getFullYear() }} Colinear.</small
      >
      <div class="flex items-center">
        <a class="md:block hidden text-sm text-gray-100 mr-4">Privacy</a>
        <a class="md:block hidden text-sm text-gray-100 mr-4">Terms</a>
        <a
          class="md:block hidden text-sm text-gray-100 mr-4"
          href="mailto:investors@colinear.io"
          >Contact Us &#8594; investors@colinear.io</a
        >
      </div>
    </div>
  </div>
</template>

<style scoped>
h2 {
  font-style: normal;
  font-weight: bold;
  font-size: 33px;
  line-height: 38px;

  color: #ffffff;
}

h3 {
  font-style: normal;
  font-weight: bold;
  font-size: 19px;
  line-height: 23px;

  color: #ffffff;
}

p {
  font-style: normal;
  font-weight: normal;
  font-size: 17px;
  line-height: 21px;

  color: #c0bfc7;
}

.flex {
  background: #131212;
}
</style>