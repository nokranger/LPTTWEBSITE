<template>
  <div>
  <b-navbar toggleable="lg" type="dark" class="header">
    <b-navbar-brand href="#">
      <div>
        <router-link to="/" ><img style="width: 120px;height: auto;margin: 10px;" src="@/assets/img/lptt-logo2.svg" alt=""></router-link>
      </div>
      </b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
        <!-- <b-nav-item href="/product"><b>Products and Services</b></b-nav-item>
        <b-nav-item href="/about"><b>About us</b></b-nav-item>
        <b-nav-item href="/contact"><b>Contact</b></b-nav-item> -->
      </b-navbar-nav>
      <b-navbar-nav class="ml-auto align-left">
        <b-nav-item href="/product"><b>Products and Services</b></b-nav-item>
        <b-nav-item href="/about"><b>About us</b></b-nav-item>
        <!-- <b-nav-item href="#"><b>Partner</b></b-nav-item> -->
        <b-nav-item href="/contact"><b>Contact</b></b-nav-item>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>
<script>
export default {}
</script>
<style scoped src="@/assets/css/header.css">
</style>
