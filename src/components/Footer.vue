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
                  <li>Operational Office : {{OperationalOffice}}</li>
                </ul>
            </div>
          </b-col>
          <b-col cols="12" sm="12" md="12" lg="4" xl="4">
            <div>
              <div class="card">
                <img v-b-modal.modal-lg src="https://i.imgur.com/TokcC60.png" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title"><i class="fa fa-location-arrow" aria-hidden="true"></i> LPTT</h5>
                  <p class="card-text">{{OperationalOffice}}</p>
                  <!-- <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p> -->
                  <div class="align-right">
                    <button class="button"><a class="linkmap" target="_blank" v-bind:href="linkOA"><img style="width:50px;height:50px;" src="https://i.imgur.com/JKjVDrz.png" alt=""></a></button>
                  </div>
                </div>
              </div>
              <b-modal hide-footer id="modal-lg" size="lg">
                <a class="linkmap" target="_blank" v-bind:href="linkOA"><img style="width:100%" src="https://i.imgur.com/TokcC60.png" class="card-img-top" alt="..."></a>
              </b-modal>
            </div>
          </b-col>
        </b-row>
        <br>
        <b-row>
          <b-container>
            <b-col>
              <div class="align-center">
               <h6>Copyright © 2019 Logiprotech (thailand) co. ltd. All Rights Reserved.Privacy Policy</h6>
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
      linkOA: 'https://www.google.com/maps/place/%E0%B8%9A%E0%B8%88%E0%B8%81.+%E0%B8%A1%E0%B9%82%E0%B8%99%E0%B8%A2%E0%B8%99%E0%B8%95%E0%B9%8C%E0%B8%8A%E0%B8%B1%E0%B8%A2/@13.7449639,100.5121174,17.17z/data=!4m5!3m4!1s0x0:0x8e45fe8733d02469!8m2!3d13.7456285!4d100.514041',
      OperationalOffice: '594 Luang Road, Pom Prab Sub-district, Pom Prap Sattru Phai District, Bangkok, 10100'
    }
  }

}
</script>
<style scoped src="@/assets/css/footer.css">

</style>
