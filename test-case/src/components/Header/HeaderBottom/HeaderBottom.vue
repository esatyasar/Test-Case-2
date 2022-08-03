<template>
    <div>
        <div class="headerBottomContainer">
            <div class="bottomMenuLink">
            <a @click="titleBeyazEsya()" class="menuLink" href="#">Beyaz Esya</a>
            <a @click="titleAyakkabi()" class="menuLink" href="#">Ayakkabi</a>
            <a @click="titleTelevizyon()" class="menuLink" href="#">Televizyonlar & Ses Sistemleri</a>
            <a @click="titleEvEsyalari()" class="menuLink" href="#">Ev Esyalari</a>
            <a @click="titleKisiselBakim()" class="menuLink" href="#">Kisisel Bakim</a>
            <a @click="titleMutfakGerecleri()" class="menuLink" href="#">Mutfak Gerecleri</a>
            </div>
        </div>
        <div class="HeaderPath">
            <h3 class="pathText">Anasayfa > <span>{{title}}</span></h3>
        </div>
        <div class="productTitle">
            <h3 class="productTitleText"><span>{{title}}</span> kategorisi icerigindeki urunler listeleniyor</h3>
        </div>
    </div>
  
</template>

<script>
export default {
  name: 'HeaderBottom',
  data(){
    return{
        title:"",
        beyazEsya:[
            {
                title:"Beko",
                link:"#",
            },
            {
                title:"Arcelik",
                link:"#"
            },
            {
                title:"Siemens",
                link:"#"
            },
            {
                title:"Samsung",
                link:"#"
            },
            {
                title:"Profilo",
                link:"#"
            },
        ],
        ayakkabi:[
            {
                title:"Nike",
                link:"#"
            },
            {
                title:"Adidas",
                link:"#"
            },
            {
                title:"Puma",
                link:"#"
            },
            {
                title:"Skechers",
                link:"#"
            },
        ],
        televizyon:[
            {
                title:"LG",
                link:"#"
            },
            {
                title:"Samsung",
                link:"#"
            },
            {
                title:"Philips",
                link:"#"
            },
            {
                title:"Vestel",
                link:"#"
            },
        ],
        evEsyalari:[
            {
                title:"Karaca",
                link:"#"
            },
            {
                title:"Jumbo",
                link:"#"
            },
            {
                title:"Madame Coco",
                link:"#"
            },
            {
                title:"English Home",
                link:"#"
            },
        ],
        kisiselBakim:[
            {
                title:"Gratis",
                link:"#"
            },
            {
                title:"Roseman",
                link:"#"
            },
            {
                title:"Watsons",
                link:"#"
            },
        ],
        mutfakGerecler:[
            {
                title:"Karaca",
                link:"#"
            },
            {
                title:"Jumbo",
                link:"#"
            },
            {
                title:"Madame Coco",
                link:"#"
            },
        ],
    }
  },
  methods:{
    titleBeyazEsya(){
        this.title = "Beyaz Esya"
    },
    titleAyakkabi(){
        this.title = "Ayakkabi"
    },
    titleTelevizyon(){
        this.title = "Televizyonlar & Ses Sistemleri"
    },
    titleEvEsyalari(){
        this.title = "Ev Esyalari"
    },
    titleKisiselBakim(){
        this.title = "Kisisel Bakim"
    },
    titleMutfakGerecleri(){
        this.title = "Mutfak Gerecleri"
    },
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss" scoped>
@import '@/scss/variables.scss';
@import '@/components/Header/HeaderBottom/HeaderBottom.scss';

</style>
