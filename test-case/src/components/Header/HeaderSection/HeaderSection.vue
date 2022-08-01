<template>
  <header>
    <HeaderTop />
    <HeaderMiddle />
  </header>
</template>

<script>
import HeaderTop from '../HeaderTop/HeaderTop.vue';
import HeaderMiddle from '../HeaderMiddle/HeaderMiddle.vue'


export default {
  name: 'HeaderSection',
  props: {
  },
  components:{
    HeaderTop,
    HeaderMiddle
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
@import '@/scss/variables.scss';
@import '@/components/Header/HeaderSection/HeaderSection.scss';

h3 {
  color:$red;
}
</style>
