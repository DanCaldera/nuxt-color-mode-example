<template>
  <div class="dark:bg-gray-800 dark:text-gray-200">
    <p class="p-4 pb-6">
      <select
        v-model="$colorMode.preference"
        class="border w-24 h-12 dark:bg-gray-900 dark:text-white dark:border-gray-700"
      >
        <option value="system">System</option>
        <option value="light">Light</option>
        <option value="dark">Dark</option>
      </select>
    </p>
    <nuxt class="relative h-screen flex overflow-hidden bg-gray-100" />
  </div>
</template>

<script>
export default {
  head: {
    title: 'Ninera Dashboard',
    meta: [
      { charset: 'utf-8' },
      { name: 'viewport', content: 'width=device-width, initial-scale=1' },
      {
        hid: 'description',
        name: 'description',
        content: 'IoT Ninera example',
      },
    ],
    link: [{ rel: 'icon', type: 'image/x-icon', href: '/favicon.ico' }],
  },
}
</script>