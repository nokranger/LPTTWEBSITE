<template>
  <div>
    <div class="partner-section">
      <div class="container-wrapper">
        <div class="container-partner">
          <div class="container-partner-title">
          </div>
            <div>
              <div class="align-center"><h1>CONTACT</h1></div>
              <br>
                <b-container class="bv-example-row">
                  <b-row>
                    <b-col cols="12" sm="12" md="12" lg="6" xl="6">
                      <div>
                        <div class="card">
                          <img v-b-modal.modal-lgc1 src="https://i.imgur.com/pdfcCXr.png" class="card-img-top" alt="...">
                          <br>
                          <div class="card-body">
                            <h5 class="card-title"><i class="fa fa-location-arrow" aria-hidden="true"></i> {{titleOA}}</h5>
                            <p class="card-text">{{detailOA}}</p><br>
                            <!-- <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p> -->
                            <div class="align-right">
                              <button class="button"><a class="linkmap" target="_blank" v-bind:href="linkOA"><img style="width:50px;height:50px;" src="https://i.imgur.com/JKjVDrz.png" alt=""></a></button>
                            </div>
                          </div>
                        </div>
                        <b-modal hide-footer id="modal-lgc1" size="lg">
                          <a class="linkmap" target="_blank" v-bind:href="linkOA"><img style="width:100%" src="https://i.imgur.com/pdfcCXr.png" class="card-img-top" alt="..."></a>
                        </b-modal>
                      </div>
                    </b-col>
                    <b-col cols="12" sm="12" md="12" lg="6" xl="6">
                      <div>
                        <div class="card">
                          <img v-b-modal.modal-lgc2 src="https://i.imgur.com/TokcC60.png" class="card-img-top" alt="...">
                          <br>
                          <div class="card-body">
                            <h5 class="card-title" style="margin-top:3px;"><i class="fa fa-location-arrow" aria-hidden="true"></i> {{titleOO}}</h5>
                            <p class="card-text">{{detailOO}}</p><br><br>
                            <!-- <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p> -->
                            <div class="align-right">
                              <button class="button"><a class="linkmap" target="_blank" v-bind:href="linkOO"><img style="width:50px;height:50px;" src="https://i.imgur.com/JKjVDrz.png" alt=""></a></button>
                            </div>
                          </div>
                        </div>
                        <b-modal hide-footer id="modal-lgc2" size="lg">
                          <a class="linkmap" target="_blank" v-bind:href="linkOO"><img style="width:100%" src="https://i.imgur.com/TokcC60.png" class="card-img-top" alt="..."></a>
                        </b-modal>
                      </div>
                    </b-col>
                  </b-row>
                </b-container>
                <br><br>
                <b-container>
                <b-row>
                  <b-col cols="6" sm="6" md="6" lg="6" xl="6">
                    <div>
                      <div class="card align-center">
                        <img style="border-radius:20%;width:70px;height:70px;margin-left:auto;margin-right:auto;margin-top:15px;" src="@/assets/img/phone.png" class="card-img-top imgzoom" alt="...">
                        <div class="card-body">
                          <h5 style="display:inline">Tel. : </h5><a href="tel:029090320"><h5 style="color:#44494c;display:inline" class="card-title">+66(0)2909-0320</h5></a><br>
                        </div>
                      </div>
                    </div>
                  </b-col>
                  <b-col cols="6" sm="6" md="6" lg="6" xl="6">
                    <div>
                      <div class="card align-center">
                        <img style="border-radius:20%;width:70px;height:70px;margin-left:auto;margin-right:auto;margin-top:15px;" src="https://i.imgur.com/yQK7Dyc.png" class="card-img-top imgzoom" alt="...">
                        <div class="card-body">
                          <h5 style="display:inline">Email : </h5><a href="mailto:info@logiprotech-th.co.th"><h5 style="color:#44494c;display:inline" class="card-title">info@logiprotech-th.co.th</h5></a><br>
                        </div>
                      </div>
                    </div>
                  </b-col>
                  <!-- <b-col cols="6" sm="6" md="6" lg="6" xl="6"><a href="tel:029090320"><img class="imgzoom" style="border-radius: 20%;width:70px;height:70px;" src="@/assets/img/phone.png" alt=""></a></b-col> -->
                  <!-- <b-col cols="6" sm="6" md="6" lg="6" xl="6"><a href="mailto:info@logiprotech-th.co.th"><img class="imgzoom" style="border-radius: 20%;width:70px;height:70px;" src="https://i.imgur.com/yQK7Dyc.png" alt=""></a></b-col> -->
                </b-row>
                </b-container>
            </div>
          <br>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data () {
    return {
      titleOA: 'Office Address',
      titleOO: 'Operational Office',
      detailOA: '55/39/1 Mhutee 13 Navanakorn Phahoyothin Road, Klong Nueng, Klong Luang, Patumtanee Thailand 12120',
      detailOO: '594 Luang Road, Pom Prab Sub-district, Pom Prap Sattru Phai District, Bangkok, 10100',
      linkOO: 'https://www.google.com/maps/place/%E0%B8%9A%E0%B8%88%E0%B8%81.+%E0%B8%A1%E0%B9%82%E0%B8%99%E0%B8%A2%E0%B8%99%E0%B8%95%E0%B9%8C%E0%B8%8A%E0%B8%B1%E0%B8%A2/@13.7456285,100.514041,15z/data=!4m5!3m4!1s0x0:0x8e45fe8733d02469!8m2!3d13.7456285!4d100.514041',
      linkOA: 'https://www.google.com/maps/place/%E0%B8%9A%E0%B8%A3%E0%B8%B4%E0%B8%A9%E0%B8%B1%E0%B8%97%E0%B8%8A%E0%B8%B1%E0%B8%A2%E0%B9%82%E0%B8%81%E0%B8%A1%E0%B8%A5%E0%B8%98%E0%B8%B8%E0%B8%A3%E0%B8%81%E0%B8%B4%E0%B8%88%E0%B8%88%E0%B8%B3%E0%B8%81%E0%B8%B1%E0%B8%94+%E0%B8%95%E0%B8%B3%E0%B8%9A%E0%B8%A5+%E0%B8%84%E0%B8%A5%E0%B8%AD%E0%B8%87%E0%B8%AB%E0%B8%99%E0%B8%B6%E0%B9%88%E0%B8%87+%E0%B8%AD%E0%B8%B3%E0%B9%80%E0%B8%A0%E0%B8%AD%E0%B8%84%E0%B8%A5%E0%B8%AD%E0%B8%87%E0%B8%AB%E0%B8%A5%E0%B8%A7%E0%B8%87+%E0%B8%9B%E0%B8%97%E0%B8%B8%E0%B8%A1%E0%B8%98%E0%B8%B2%E0%B8%99%E0%B8%B5+12120/@14.122681,100.6073938,17z/data=!3m1!4b1!4m5!3m4!1s0x30e27f5d2303305b:0x133eb0b70c9597c4!8m2!3d14.1226758!4d100.6095825'
    }
  },
  created () {
    document.title = 'Contact LPTT - LPTT'
  }

}
</script>
<style scoped src="@/assets/css/contact.css">

</style>
