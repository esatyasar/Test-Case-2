<template>
  <footer class="footer">
    <div class="footerMenuContainer">
      <div>
        <h3 href="#">Kurumsal</h3>
        <p href="#">Hakkimizda</p>
        <p href="#">Kampanyalar</p>
        <p href="#">Banka Hesap Numaralari</p>
        <p href="#">Blog</p>
        <p href="#">Haberler</p>
      </div>
      <div>
        <h3 href="#">Musteri Hizmetleri</h3>
        <p href="#">Siparis Sorgulama</p>
        <p href="#">Teslimat ve Kargo</p>
        <p href="#">Iade ve Degisim</p>
        <p href="#">Uyelik Sozlesmesi</p>
        <p href="#">Gizlilik ve Guvenlik</p>
      </div>
      <div>
        <h3>Yardim</h3>
        <p href="#">Iletisim Bilgileri</p>
        <p href="#">Sikca Sorulan Sorular</p>
      </div>
      <div>
        <h3>Iletisim</h3>
        <p> <span>Adres:</span> 1376 Sok. No:1/43 Boran Plaza, Halkapinar, Konak/Izmir</p>
        <p> <span>Telefon:</span> 08505555555</p>
      </div>
      <div>
        <div>
          <h3>Bizi Takip Edin</h3>
          <i class="fa-brands fa-facebook-f"></i>
          <i class="fa-brands fa-twitter"></i>
          <i class="fa-brands fa-youtube"></i>
          <i class="fa-brands fa-instagram"></i>
        </div>
        <div class="mailTitle">
          <p>E-bultene abone olun, gorusmeleri kacirmayin</p>
          <div class="mailSection">
            <input type="text" class="sendEmail" placeholder="E-posta Adresiniz">
            <button><i class="fa-solid fa-right-long"></i></button>
          </div>
        </div>
        
      </div>
    </div>
    <hr class="line">
    <div class="footerBottom">
      <div class="footerBottomLeft">
        <p>Copyright © 2022 Karma-Kirmizi</p>
      </div>
      <div class="footerBottomRight">
        <img class="footerLogo" src="../../../assets/logo.png" alt="logo" href="#">
      </div>

    </div>
   
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

</style>
