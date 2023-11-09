<template>
    <section>
        <div class="container position-relative">
            <div class="row">

              <!-- 1 column -->
              <div class="col-auto">
                <h5>DC COMICS</h5>
                <ul>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Characters</a></li>
                </ul>
                
                <h5>SHOP</h5>
                <ul>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Shop DC Collectibles</a></li>
                </ul>
              </div>
              
              <!-- 2 column -->
              <div class="col-auto">
                <h5>DC</h5>
                <ul>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Privacy policy (New)</a></li>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Characters</a></li>
                  <li><a href="#">Characters</a></li>
                </ul>
              </div>
              
              <!-- 3 column -->
              <div class="col-auto">
                <h5>SITES</h5>
                <ul>
                  <li><a href="#">DC</a></li>
                  <li><a href="#">MAD Magazine</a></li>
                  <li><a href="#">DC Kids</a></li>
                  <li><a href="#">DC Universe</a></li>
                  <li><a href="#">DC Power VIsa</a></li>
                </ul>
              </div>
            </div>
            <img src="../../assets/img/dc-logo-bg.png" alt="">
          </div>
    </section>
</template>

<script>
  export default {
    name: 'FooterMiddle',
    
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
    background-image: url('../../assets/img/footer-bg.jpg');
    background-size: cover;
    padding: 3rem 0;
    color: $white;
    overflow: hidden;
  }
      
  a 
  {
    color: $footer-text;
    font-size: 0.8rem;
    display: block;
    padding: 2px 0;
  }

  img
  {
    position: absolute;
    right: 0;
    top: 50%;
    transform: translate(0, -50%);
  }
    

</style>