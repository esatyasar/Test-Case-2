<template>
  <div class="headerTopContainer">
    <div class="headerTopLeft">
      <i class="fa-brands fa-facebook-f"></i>
      <i class="fa-brands fa-twitter"></i>
      <i class="fa-brands fa-youtube"></i>
      <i class="fa-brands fa-instagram"></i>
    </div>
    <div class="HeaderTopRight">
      <div class="helpTitle">
        <h3>Yardim</h3>
      </div>
      <div class="blogTitle">
        <h3>Blog</h3>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HeaderTop',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
@import '@/scss/variables.scss';
@import '@/components/Header/HeaderTop/HeaderTop.scss';

</style>
