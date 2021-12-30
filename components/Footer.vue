<template>
  <div class="flex flex-col antialiased px-32 pt-28 pb-12">
    <div class="flex justify-between">
      <div class="flex flex-col w-1/3">
        <h2 class="font-roboto" data-aos="fade-in">Start building with <br> Colinear today.</h2>
        <button
          class="
            flex
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
      <div class="flex flex-col w-1/4 mt-1">
        <h3 class="mb-8" data-aos="fade-in">Quick start</h3>
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
      <div class="flex flex-col w-1/5 mt-1">
        <h3 class="mb-8" data-aos="fade-in">Community</h3>
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
    <hr class="border-t border-neutral-700 mt-20 mb-12">
    <div class="flex justify-between items-center">
        <small class="text-sm text-gray-100">Copyright © {{ new Date().getFullYear() }} Colinear.</small>
        <div class="flex items-center">
            <a class="text-sm text-gray-100 mr-4">Privacy</a>
            <a class="text-sm text-gray-100 mr-4">Terms</a>
            <a class="text-sm text-gray-100 mr-4" href="mailto:investors@colinear.io">Contact Us &#8594; investors@colinear.io</a>
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