<template>
  <div class="footer">
      <p>copyright Airvault&copy;{{ getCurrentYear }}</p>
  </div>
</template>

<script>
export default {
  name: 'Footer',
  computed: {
    getCurrentYear() {
        return new Date().getFullYear();
    }
  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
.footer {
    background-color:#BFEBFF;
    min-height:6rem;
    font-weight:bold;
    padding-top:2rem;
    position:fixed;
    bottom:0;
    width:100%;
}

</style>