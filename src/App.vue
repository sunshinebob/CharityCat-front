<template>
  <div id="app">
  </div>
</template>

<script type="text/ecmascript-6">
  export default {
    created() {
      const year = 2016
      const month = 2
      const days = new Date(year, month, 0).getDate()
      console.log(days)
    }
  }
</script>

<style scoped lang="sass" rel="stylesheet/sass">

</style>
