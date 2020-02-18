<template>
  <div>
  <b-navbar toggleable="lg" type="dark" class="header">
    <b-navbar-brand href="#">
      <div>
        <router-link to="/" ><img style="width: 120px;height: auto;margin: 10px;" src="@/assets/img/lptt-logo2.svg" alt="logoprotech logo"></router-link>
      </div>
      </b-navbar-brand>

    <b-navbar-toggle target="nav-collapse"></b-navbar-toggle>

    <b-collapse id="nav-collapse" is-nav>
      <b-navbar-nav>
      </b-navbar-nav>
      <b-navbar-nav class="ml-auto align-left">
        <b-nav-item href="/"><b>Home</b></b-nav-item>
        <b-nav-item href="/product"><b>Products and Services</b></b-nav-item>
        <b-nav-item href="#"><b id="popover-button-open">Customers</b></b-nav-item>
        <b-nav-item href="/about"><b>About us</b></b-nav-item>
        <b-nav-item href="/contact"><b>Contact</b></b-nav-item>
          <b-popover target="popover-button-open" placement="top">
            <template v-slot:title>Customers</template>
            <a target="_blank" href="https://ubisense.com/customers/" style="white-space: nowrap;color:#44494c;font-size: medium;">Abroad achievement stories</a> || <a v-b-modal.modal-lgcm style="white-space: nowrap;color:#44494c;font-size: medium;">Thailand projects</a>
              <b-modal hide-footer id="modal-lgcm" size="lg" style="position: relative;">
                <b-contanier>
                  <b-row>
                    <b-col cols="12" sm="12" md="12" lg="12" xl="12">
                      <h4 class="align-center" style="font-style:italic;">"{{qoute}}"</h4><br>
                    </b-col>
                  </b-row>
                  <b-row>
                    <b-col class="align-left" cols="6" sm="6" md="6" lg="6" xl="6">
                      <br>
                      <img style="width:95%;height:auto;" class="imgc" src="@/assets/img/toyota2.jpg" alt="logoprotech x toyota">
                    </b-col>
                    <b-col class="align-right" cols="6" sm="6" md="6" lg="6" xl="6">
                      <img style="width:70%;height:auto;margin-right:50px;" class="imgc" src="@/assets/img/tbs.jpg" alt="logoprotech x tbs">
                    </b-col>
                    <b-col class="align-right" cols="6" sm="6" md="6" lg="6" xl="6">
                      <br>
                      <img class="imgc" src="@/assets/img/tag_new.png" alt="logoprotech x tag">
                    </b-col>
                    <b-col class="align-left" cols="6" sm="6" md="6" lg="6" xl="6">
                      <img style="width:70%;height:auto;margin-top:-20px;margin-left:50px;" class="imgc" src="@/assets/img/tapp.jpg" alt="logoprotech x tapp">
                    </b-col>
                  </b-row>
                  <b-row>
                    <b-col cols="12" sm="12" md="12" lg="12" xl="12">
                      <h4 class="align-center" style="font-style:italic;">"{{qoute2}}"</h4><br>
                      <h4>Email : <a style="color:#44494c;" href="mailto:info@logiprotech-th.co.th">info@logiprotech-th.co.th</a></h4><br>
                      <h4>Tel. : <a style="color:#44494c;" href="tel:029090320">+66(0)2909-0320</a></h4>
                    </b-col>
                  </b-row>
                </b-contanier>
              </b-modal>
          </b-popover>
      </b-navbar-nav>
    </b-collapse>
  </b-navbar>
</div>
</template>
<script>
export default {
  data () {
    return {
      qoute: 'Main Customers in Thailand',
      qoute2: 'For project achievements in thailand please contact us'
    }
  }
}
</script>
<style scoped src="@/assets/css/header.css">
</style>
