<template>
  <div class="flex items-center text-sm bg-black text-gray-200 px-5 tracking-wide py-5" v-if="isVisible">
    <p>Join the best payment gateway for global commerce. See how we're</p> &nbsp; <a class="text-teal-400" href="#">changing the status quo.</a>
    <svg xmlns="http://www.w3.org/2000/svg" class="h-4 w-4 cursor-pointer ml-auto" fill="none" viewBox="0 0 24 24" stroke="currentColor" @click="hide">
      <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 18L18 6M6 6l12 12" />
    </svg>
  </div>
</template>

<script>
export default {
  name: 'Alert',
  props: {
    message: {
      type: String,
      required: false
    }
  },
  data() {
    return {
      isVisible: true
    }
  },
  methods: {
    hide() {
      this.isVisible = false
    }
  }
}
</script>