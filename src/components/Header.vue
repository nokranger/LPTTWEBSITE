<template>
  <!-- <div>
    <nav class="container-navbar">
      <div class="container-wrapper-navbar">
        <div id="nav-logo" class="container-navbar-logo">
          <a data-scroll="" class="home" href="#home"><img src="@/assets/img/lptt-logo.svg" alt="logo appman"></a>
        </div>
        <div id="nav-sec" class="container-navbar-section">
          <div>
            <a data-scroll="" class="nav-sec-detail" href="#aboutUs" style="display: block;" v-b-modal.modal-1>Product&Service</a>
              <b-modal id="modal-1" title="BootstrapVue">
                <img src="@/assets/img/lptt-logo.svg" alt="">
                <p class="my-4">Hello from modal!</p>
              </b-modal>
          </div>
          <a data-scroll="" class="nav-sec-detail" href="#career" style="display: block;">About</a>
          <a data-scroll="" class="nav-sec-detail" href="#contact" style="display: block;">Partner</a>
          <a data-scroll="" class="nav-sec-detail" href="#contact" style="display: block;">Contact us</a>
          <i class="top-nav-icon">
            <i class="close-icon" id="close-icon" style="display: none;"><img src="@/assets/img/closeIcon.svg" alt="icon close"></i>
            <i class="open-icon" id="open-icon" style="display: block;"><img src="@/assets/img/openIcon.svg" alt="icon open"></i>
          </i>
        </div>
      </div>
    </nav>
  </div> -->
  <div>
  <b-navbar toggleable="lg" type="dark" class="header">
    <b-navbar-brand href="#">
      <div>
        <router-link to="/" ><img style="width: 120px;height: auto;margin: 10px;" src="@/assets/img/lptt-logo2.svg" alt=""></router-link>
      </div>
      </b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav class="align-left">
        <b-nav-item href="/product"><b>Product and Service</b></b-nav-item>
        <b-nav-item href="/about"><b>About</b></b-nav-item>
        <b-nav-item href="/partner"><b>Partner</b></b-nav-item>
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
