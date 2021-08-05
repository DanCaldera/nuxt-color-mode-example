<!-- Please remove this file from your project -->
<template>
  <div class="px-4 mx-auto max-w-screen-sm md:max-w-screen-md md:p-0 lg:max-w-screen-lg xl:max-w-screen-xl">
    <div class="min-h-screen flex justify-center items-center">
      <header>
        <p class="sm:text-lg sm:leading-snug font-semibold tracking-wide uppercase text-emerald-500 dark:text-emerald-400 mb-3">
          TailwindCSS v2.0
        </p>
        <h1 class="text-gray-900 dark:text-white text-3xl sm:text-5xl lg:text-6xl leading-none font-extrabold tracking-tight mb-8">Dark Mode Template</h1>
        <div class="text-gray-500 dark:text-gray-400 text-lg sm:text-2xl font-normal sm:leading-10 space-y-6 mb-6">
          <p>This is a boilerplate template built with official features from version 2.0!</p>
        </div>
      </header>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      number: 2,
    }
  },

  mounted() {},

  methods: {
    increment() {
      this.number++
    },
  },
}
</script>

