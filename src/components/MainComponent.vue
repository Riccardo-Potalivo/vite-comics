<template>
    <main>
        <section class="container">
            <h3>-- Content goes here --</h3>
        </section>
    </main>
</template>

<script>
  export default {
    name: 'MainComponent',
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
    @use '../assets/style/partials/variables' as *;
    
    main
    {
        background-color: $bg-main;
        color: $white;
        padding: 40px 0;
    }

</style>