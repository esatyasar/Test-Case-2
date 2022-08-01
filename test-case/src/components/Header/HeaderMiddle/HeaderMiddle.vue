<template>
    <div class="HeaderMiddleContainer">
        <div class="logo">
            <h1>Karma </h1>
            <h6 >EVİNİZİN YANINDA</h6>
        </div>
        <div class="searchSection">
            <input 
                class="searchBar"
                type="text" 
                name="search" 
                id="search" 
                placeholder="Ne Aramistiniz.."
            > 
            <i class="fa-solid fa-magnifying-glass"></i>
        </div>
        <div class="UserCartSection">
            <div class="userSection">
                <i class="fa-solid fa-user"></i>        
                <p>Giris Yap</p>
                <p><span style="font-size:8px;">veya uye ol</span>"></p>
                <i class="fa-light fa-angle-down"></i>
            </div>
            <div class="cartSection">
                <i class="fa-solid fa-cart-shopping"></i>
                <p>Sepet</p>
                <p>0.00TL</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'HeaderMiddle',
  props: {
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
@import '@/scss/variables.scss';
@import '@/components/Header/HeaderMiddle/HeaderMiddle.scss';

</style>
