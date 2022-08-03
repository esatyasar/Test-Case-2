<template>
    <div>
      <HeaderSection/>
      <MainSection/>
      <FooterSection/>
    </div>
</template>

<script>
import HeaderSection from './components/Header/HeaderSection/HeaderSection.vue'
import MainSection from './components/MainContent/MainSection/MainSection.vue'
import FooterSection from './components/Footer/FooterSection/FooterSection.vue'


export default {
  name: 'App',
  components: {
    HeaderSection,
    MainSection,
    FooterSection
  }
}
</script>

<style>
@import url("https://fonts.googleapis.com/css?family=Roboto+Condensed");

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

#app {
  font-family: "Roboto", sans-serif;
}


</style>
