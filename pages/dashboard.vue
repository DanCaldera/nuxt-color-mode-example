<template>
  <div>
    Hola!
  </div>
</template>

<script>
export default {
  layout: 'dashboard',

  data() {
    return {}
  },

  created() {
    // console.log('created: ', Date.now())
  },

  mounted() {
    // console.log('mounted', Date.now())
    this.increment()
  },

  methods: {
    increment() {
      this.number++
    },
  },
}
</script>
