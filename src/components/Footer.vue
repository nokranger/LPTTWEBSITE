<template>
<div>
  <link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.8/css/all.css" integrity="sha384-3AB7yXWz4OeoZcPbieVW64vVXEwADiYyAEhwilzWsLw+9FgqpyjjStpPnpBO8o8S" crossorigin="anonymous">
  <div class="footer align-left">
    <br>
    <div>
      <b-container>
        <div>
          <img class="lpttlogo" src="@/assets/img/lptt-logo2.svg" alt="lpttlogo">
        </div>
        <br>
        <b-row>
          <b-col cols="12" sm="12" md="12" lg="4" xl="4">
            <div>
              <h3>Products</h3>
              <ul class="footers">
                <li>RTLS (Real-Time Location Services)</li>
                <li>Smart Factory</li>
                <li>Operating other IOTs</li>
              </ul>
              <div>
                <h3>Services</h3>
                <ul class="footers">
                  <li>We study and analyse IoT devices to develop a tailored system to comply with customer requirements.</li>
                </ul>
              </div>
            </div>
          </b-col>
          <b-col cols="12" sm="12" md="12" lg="4" xl="4">
            <div>
              <h3>Contact</h3>
                <ul class="footers">
                  <li>Email : <a href="mailto:info@logiprotech-th.co.th">info@logiprotech-th.co.th</a></li>
                  <li>Tel. : <a href="tel:029090320">+66(0)2909-0320</a></li>
                  <li>Operational Office : 19/125 Soi Sukhumvit 13, Klong Toey Nua, Wattana, Bangkok 10110, Thailand</li>
                </ul>
            </div>
          </b-col>
          <b-col cols="12" sm="12" md="12" lg="4" xl="4">
            <div>
              <div v-b-modal.modal-lg class="card">
                <img src="https://i.imgur.com/CdVCi8i.png" class="card-img-top" alt="logiprotech logo">
                <div class="card-body">
                  <h5 class="card-title"><i class="fa fa-location-arrow" aria-hidden="true"></i> LPTT</h5>
                  <p class="card-text">19/125 Soi Sukhumvit 13, Klong Toey Nua, Wattana, Bangkok 10110, Thailand</p>
                  <!-- <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p> -->
                  <div class="align-right">
                    <button class="button"><a class="linkmap" target="_blank" v-bind:href="linkOA"><img style="width:50px;height:50px;" src="https://i.imgur.com/JKjVDrz.png" alt="map logiprotech"></a></button>
                  </div>
                </div>
              </div>
              <b-modal hide-footer id="modal-lg" size="lg">
                <a class="linkmap" target="_blank" v-bind:href="linkOA"><img style="width:100%" src="https://i.imgur.com/CdVCi8i.png" class="card-img-top" alt="map logiprotech"></a>
              </b-modal>
            </div>
          </b-col>
        </b-row>
        <br>
        <b-row>
          <b-container>
            <b-col>
              <div class="align-center">
               <h6 style="font-size:14px;">Copyright © 2019 Logiprotech (thailand) co. ltd. All Rights Reserved.Privacy Policy</h6>
              </div>
              <br>
            </b-col>
          </b-container>
        </b-row>
      </b-container>
    </div>
  </div>
</div>
</template>
<script>
export default {
  data () {
    return {
      linkOA: 'https://www.google.co.th/maps/place/LOGIPROTECH+(THAILAND)+CO.,LTD./@13.7428174,100.5554025,17z/data=!3m1!4b1!4m5!3m4!1s0x30e29f468d5f8f5b:0x2085bde87d87f06b!8m2!3d13.7428122!4d100.5575912?hl=th'
    }
  }

}
</script>
<style scoped src="@/assets/css/footer.css">

</style>
