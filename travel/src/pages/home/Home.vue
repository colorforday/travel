<template>
  <div>
    <HomeHeader></HomeHeader>
    <HomeIcons></HomeIcons>
  </div>
</template>

<script>
  import HomeHeader from './components/Header'
  import HomeIcons from './components/Icons'

  export default {
    name: 'Home',
    components: {
      HomeHeader,HomeIcons
    }
  }
</script>

<style>

</style>
