<template>
    <section>
        <div class="container">
          <div class="row g-0">
            <div class="col-6 col-md-4 col-lg-3 col-xxl-2 p-3" v-for="series in currentSeries">
              <div class="img_container">
                <img :src="series.thumb" alt="">
              </div>
              <p class="mt-3">{{ series.series.toUpperCase() }}</p>

            </div>

          </div>
        </div>
    </section>
</template>

<script>
  import {currentSeries} from '../../data/data.js';
  console.log(currentSeries[5].price)
  export default {
    name: 'MainContent',
    data(){
      return {
        currentSeries: currentSeries

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
        background-color: $bg-main;
        color: $white;
        padding: 3rem 0;
    }
    // .container
    // {
    //     height: 15rem;
    // }
    .img_container
    {
      width: 100%;
      aspect-ratio: 1;
    }

    img
    {
      width: 100%;
      height: 100%;
      object-fit: cover;
      object-position: top;
    }

</style>