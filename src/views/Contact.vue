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
                        <div v-b-modal.modal-lgc1 class="card">
                          <img src="https://i.imgur.com/pdfcCXr.png" class="card-img-top" alt="map ckb">
                          <br>
                          <div class="card-body">
                            <h5 class="card-title"><i class="fa fa-location-arrow" aria-hidden="true"></i> {{titleOA}}</h5>
                            <p class="card-text">{{detailOA}}</p><br>
                            <div class="align-right">
                              <button class="button"><a class="linkmap" target="_blank" v-bind:href="linkOA"><img style="width:50px;height:50px;" src="https://i.imgur.com/JKjVDrz.png" alt="map ckb"></a></button>
                            </div>
                          </div>
                        </div>
                        <b-modal hide-footer id="modal-lgc1" size="lg">
                          <a class="linkmap" target="_blank" v-bind:href="linkOA"><img style="width:100%" src="https://i.imgur.com/pdfcCXr.png" class="card-img-top" alt="map ckb"></a>
                        </b-modal>
                      </div>
                    </b-col>
                    <b-col cols="12" sm="12" md="12" lg="6" xl="6">
                      <div>
                        <div v-b-modal.modal-lgc2 class="card">
                          <img src="https://i.imgur.com/Mvqg7IP.png" class="card-img-top" alt="map logiprotech">
                          <br>
                          <div class="card-body">
                            <h5 class="card-title" style="margin-top:3px;"><i class="fa fa-location-arrow" aria-hidden="true"></i> {{titleOO}}</h5>
                            <p class="card-text">{{detailOO}}</p><br><br>
                            <div class="align-right">
                              <button class="button"><a class="linkmap" target="_blank" v-bind:href="linkOO"><img style="width:50px;height:50px;" src="https://i.imgur.com/JKjVDrz.png" alt="map logiprotech"></a></button>
                            </div>
                          </div>
                        </div>
                        <b-modal hide-footer id="modal-lgc2" size="lg">
                          <a class="linkmap" target="_blank" v-bind:href="linkOA"><img style="width:100%" src="https://i.imgur.com/Mvqg7IP.png" class="card-img-top" alt="map logiprotech"></a>
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
                        <img style="border-radius:20%;width:70px;height:70px;margin-left:auto;margin-right:auto;margin-top:15px;" src="@/assets/img/phone.png" class="card-img-top imgzoom" alt="">
                        <div class="card-body">
                          <h5 style="display:inline">Tel. : </h5><a href="tel:029090320"><h5 style="color:#44494c;display:inline" class="card-title">+66(0)2909-0320</h5></a><br>
                        </div>
                      </div>
                    </div>
                  </b-col>
                  <b-col cols="6" sm="6" md="6" lg="6" xl="6">
                    <div>
                      <div class="card align-center">
                        <img style="border-radius:20%;width:70px;height:70px;margin-left:auto;margin-right:auto;margin-top:15px;" src="https://i.imgur.com/yQK7Dyc.png" class="card-img-top imgzoom" alt="">
                        <div class="card-body">
                          <h5 style="display:inline">Email : </h5><a href="mailto:info@logiprotech-th.co.th"><h5 style="color:#44494c;display:inline" class="card-title">info@logiprotech-th.co.th</h5></a><br>
                        </div>
                      </div>
                    </div>
                  </b-col>
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
      titleOA: 'Office address',
      titleOO: 'Operational Office',
      detailOA: '55/39/1 Mhutee 13 Navanakorn Phahoyothin Road, Klong Nueng, Klong Luang, Patumtanee Thailand 12120',
      detailOO: '19/125 Soi Sukhumvit 13, Klong Toey Nua, Wattana, Bangkok 10110, Thailand',
      linkOA: 'https://www.google.com/maps/place/%E0%B8%9A%E0%B8%A3%E0%B8%B4%E0%B8%A9%E0%B8%B1%E0%B8%97%E0%B8%8A%E0%B8%B1%E0%B8%A2%E0%B9%82%E0%B8%81%E0%B8%A1%E0%B8%A5%E0%B8%98%E0%B8%B8%E0%B8%A3%E0%B8%81%E0%B8%B4%E0%B8%88%E0%B8%88%E0%B8%B3%E0%B8%81%E0%B8%B1%E0%B8%94+%E0%B8%95%E0%B8%B3%E0%B8%9A%E0%B8%A5+%E0%B8%84%E0%B8%A5%E0%B8%AD%E0%B8%87%E0%B8%AB%E0%B8%99%E0%B8%B6%E0%B9%88%E0%B8%87+%E0%B8%AD%E0%B8%B3%E0%B9%80%E0%B8%A0%E0%B8%AD%E0%B8%84%E0%B8%A5%E0%B8%AD%E0%B8%87%E0%B8%AB%E0%B8%A5%E0%B8%A7%E0%B8%87+%E0%B8%9B%E0%B8%97%E0%B8%B8%E0%B8%A1%E0%B8%98%E0%B8%B2%E0%B8%99%E0%B8%B5+12120/@14.122681,100.6073938,17z/data=!3m1!4b1!4m5!3m4!1s0x30e27f5d2303305b:0x133eb0b70c9597c4!8m2!3d14.1226758!4d100.6095825',
      linkOO: 'https://www.google.co.th/maps/place/LOGIPROTECH+(THAILAND)+CO.,LTD./@13.7428174,100.5554025,17z/data=!3m1!4b1!4m5!3m4!1s0x30e29f468d5f8f5b:0x2085bde87d87f06b!8m2!3d13.7428122!4d100.5575912?hl=th'
    }
  },
  metaInfo () {
    return {
      title: 'Contact LPTT - LPTT',
      meta: [
        {
          name: 'description',
          content: 'LOGIPROTECH (THAILAND) CO.,LTD. Website'
        },
        {
          name: 'keywords',
          content: 'Lptt company website, lptt website, iot, smart factory, RTLS (Real-Time Location Services) Smart Factory, RTLS,real time location systems, rfid solution, rfid, business process design system architect'
        }
      ]
    }
  }

}
</script>
<style scoped src="@/assets/css/contact.css">

</style>
