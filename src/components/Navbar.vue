<template>
  <b-navbar class="navbar" toggleable="md" type="dark" variant="info">
    <b-navbar-brand href="#">Andrew Madden</b-navbar-brand>

  </b-navbar>
</template>

<script>
export default {
  name: 'Navbar',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
  .navbar {
    height: 130px;
  }
  
  .navbar > div {
    height: 100px;
    width: 100px;
    border-radius: 100px;
    background-image: url("../assets/DSC01817-2.jpg");
    background-position: inherit;
  }
</style>
