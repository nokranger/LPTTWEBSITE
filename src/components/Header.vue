<template>
  <div>
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
  </div>
</template>
<script>
export default {}
</script>
<style scoped src="@/assets/css/header.css">
</style>
