<template>
<div>
  <b-navbar type="dark" variant="dark">
    <b-navbar-nav>
      <b-nav-item href="#">Home</b-nav-item>

      <!-- Navbar dropdowns -->
      <b-nav-item-dropdown text="Lang" right>
        <b-dropdown-item href="#">A</b-dropdown-item>
        <b-dropdown-item href="#">B</b-dropdown-item>
        <b-dropdown-item href="#">C</b-dropdown-item>
        <b-dropdown-item href="#">D</b-dropdown-item>
      </b-nav-item-dropdown>

      <b-nav-item-dropdown text="User" right>
        <b-dropdown-item href="#">Account</b-dropdown-item>
        <b-dropdown-item href="#">Settings</b-dropdown-item>
      </b-nav-item-dropdown>
    </b-navbar-nav>
  </b-navbar>
</div>
</template>
<script>
export default {
}
</script>
<style scoped src="@/assets/css/header.css">

</style>
