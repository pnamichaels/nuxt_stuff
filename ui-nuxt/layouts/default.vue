<template>
  <div>
    <ul class="menu align-center">
      <li><nuxt-link to="/">home</nuxt-link></li>
      <li><nuxt-link to="/form">form</nuxt-link></li>
      <li><nuxt-link to="/">Motion UI</nuxt-link>></li>
    </ul>
    <nuxt />
  </div>
</template>

<script>
export default {
  mounted () {
    this.$getCurrentScreenSize()
  }  
}
</script>
