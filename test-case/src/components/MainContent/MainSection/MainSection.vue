<template>
  <main>
    <h3>
      Main Section  
    </h3>
  </main>
</template>

<script>
export default {
  name: 'MainSection',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
@import '@/scss/variables.scss';
@import '@/components/MainContent/MainSection/MainSection.scss';

h3 {
  margin: 40px 0 0;
  color:$blue;
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
