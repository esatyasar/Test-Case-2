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
            <div class="searchIcon">
                <i class="fa-solid fa-magnifying-glass"></i>
            </div>
        </div>
        <div class="UserCartSection">
            <div class="userSection">
                <div class="userIcon">
                    <i class="fa-solid fa-user"></i>        
                </div>
                <div class="userText">
                    <h4 class="userLogin">Giris Yap</h4>
                    <h3 class="userSignup">veya uye ol</h3>
                </div>
                <div class="userAngleDown">
                    <i class="fa-solid fa-angle-down"></i> 
                </div>
            </div>
            <div class="cartSection">
                <div class="cartIcon">
                    <i class="fa-solid fa-cart-shopping"></i>
                </div>
                <div class="cartText">
                    <h4 class="cartTitle">Sepet</h4>
                    <h4 class="cartAmount">0.00TL</h4>
                </div>
                
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
