<template>
    <section>
        <div class="container d-flex justify-content-around">
            <div class="d-flex align-items-center gap-3">
                <img src="../../assets/img/buy-comics-digital-comics.png" alt="">
                <a href="#">DIGITAL COMICS</a>
            </div>
            <div class="d-flex align-items-center gap-3">
                <img src="../../assets/img/buy-comics-digital-comics.png" alt="">
                <a href="#">DIGITAL COMICS</a>
            </div>
            <div class="d-flex align-items-center gap-3">
                <img src="../../assets/img/buy-comics-digital-comics.png" alt="">
                <a href="#">DIGITAL COMICS</a>
            </div>
            <div class="d-flex align-items-center gap-3">
                <img src="../../assets/img/buy-comics-digital-comics.png" alt="">
                <a href="#">DIGITAL COMICS</a>
            </div>
            <div class="d-flex align-items-center gap-3">
                <img src="../../assets/img/buy-comics-digital-comics.png" alt="">
                <a href="#">DIGITAL COMICS</a>
            </div>
        </div>
    </section>
</template>

<script>
  export default {
    name: 'FooterTop',

    data(){
      return {

      }
    },

    methods: {

    },

    computed: {

    }
  }
</script>

<style lang="scss" scoped>
    @use '../../assets/style/partials/variables' as *;

    section
    {
        background-color: $primary;
        color: $white;
        padding: 3rem 0;
    }

    a 
    {
        text-decoration: none;
        color: inherit;
    }

    img 
    {
        height: 60px;
    }
    

</style>