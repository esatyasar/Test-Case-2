<template>
  <footer>
    <h3>
      Footer Section
    </h3>
  </footer>
</template>

<script>
export default {
  name: 'FooterSection',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
@import '@/scss/variables.scss';
@import '@/components/Footer/FooterSection/FooterSection.scss';
h3 {
  margin: 40px 0 0;
  color:$black;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: $yellow;
}
</style>
