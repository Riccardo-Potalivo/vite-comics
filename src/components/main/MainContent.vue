<template>
    <section>
        <div class="container">
        </div>
    </section>
</template>

<script>
  export default {
    name: 'MainContent',
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
        background-color: $bg-main;
        color: $white;
    }
    .container
    {
        height: 15rem;
    }

</style>