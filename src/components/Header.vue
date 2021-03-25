<template>
  <div class="header">
      <div class="nav">
      <router-link class="nav__link nav__link--home" to="/">Home</router-link>
      <router-link class="nav__link" to="/about">About</router-link>
      <router-link class="nav__link" to="/contact">Contact</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Header',
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">

.nav {
  padding: 30px;

  a {
    font-weight: bold;
    color: #2c3e50;
    margin:0 1rem;

    &.router-link-exact-active {
      color: #45C5FF;
    }
  }
}
a.nav__link.nav__link--home {
    width:60px;
}
</style>
