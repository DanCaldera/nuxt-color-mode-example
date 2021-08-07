<template>
  <nuxt class="relative h-screen flex overflow-hidden bg-gray-100" />
</template>

<script>
export default {
  head: {
    title: 'Ninera',
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