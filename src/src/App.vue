<template>
  <div id="app">
    <MyHeader></MyHeader>
    <h1> Some content... </h1>
    <MyFooter></MyFooter>
  </div>
</template>

<script>
import Header from '@/components/Header'
import Footer from '@/components/Footer'

export default {
    components: {
        'MyHeader': Header,
        'MyFooter': Footer,
    }
}
</script>

<style scoped lang="sass">
html, body
  margin: 0
  min-height: 100vh
</style>
