<template>
  <div>
    <h1>{{ $t('home.signup-feedback') }}</h1>
    <button @click="exit">Return to homepage</button>
  </div>
</template>

<script>
export default {
  methods: {
    exit() {
      this.$router.push({ name: 'index' })
    },
  },
}
</script>
