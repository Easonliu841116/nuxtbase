<template>
  <div>
    <h1>Test</h1>
  </div>
</template>

<script>
export default {
  
}
</script>

<style lang="sass">
@import '@/sass/mixins'
h1
  color: red
  @include pad
    color: green
</style>
