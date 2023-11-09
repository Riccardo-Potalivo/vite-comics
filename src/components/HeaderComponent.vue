<template>
    <header>
        <nav class="container d-flex align-items-center justify-content-between py-3">
            <a class="navbar-brand" href="#">
                <img src="../assets/img/dc-logo.png" alt="logo">
            </a>
            <ul class="nav justify-content-end">
              <li class="nav-item">
                <a class="nav-link active" href="#">Active</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Link</a>
              </li>
              <li class="nav-item">
                <a class="nav-link disabled" href="#">Disabled</a>
              </li>
            </ul>
        </nav>
    </header>
</template>

<script>
  export default {
    name: 'HeaderComponent',
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

  nav img
  {
    width: 80px;
  }

</style>