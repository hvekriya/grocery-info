<template>
  <div>
    <b-navbar type="dark" variant="info" toggleable="lg">

      <b-navbar-toggle target="nav_collapse"></b-navbar-toggle>
    
      <b-navbar-brand href="/" class="d-lg-none">Harry's Gym</b-navbar-brand>
    
      <b-collapse is-nav id="nav_collapse">
        <b-navbar-nav>
          <b-nav-item href="#">Home</b-nav-item>
          <b-nav-item href="#">Protein</b-nav-item> 
          <b-nav-item href="#">Apparel</b-nav-item>       
      </b-collapse>
    </b-navbar>
  </div>
</template>

<script>
  export default {
    name: 'Nav'
  }
</script>

<style>

</style>