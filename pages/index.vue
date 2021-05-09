<template>
  <div>
  </div>
</template>

<script>
export default {
  async mounted() {
    console.log(
      JSON.stringify(await this.$axios.$get('https://qiita.com/api/v2/tags/"nuxt.js"/items'))
    )
  }
}
</script>

<style>
</style>

