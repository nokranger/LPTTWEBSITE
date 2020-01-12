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
                <!-- <div class="align-left">
                    <ul class="address align-center">
                        <li>{{titleOA}}
                            <ul class="address">{{detailOA}}
                                <li class="align-center"><button><a target="_blank" v-bind:href="linkOA">View Google Map</a></button></li>
                            </ul>
                        </li>
                        <li>{{titleOO}}
                            <ul class="address">{{detailOO}}
                                <li class="align-center"><button><a target="_blank" v-bind:href="linkOO">View Google Map</a></button></li>
                            </ul>
                        </li>
                    </ul>
                </div> -->
                <b-container class="bv-example-row">
                  <b-row>
                    <b-col cols="12" sm="12" md="12" lg="6" xl="6">
                      <div>
                        <div class="card">
                          <img src="https://i.imgur.com/CdVCi8i.png" class="card-img-top imgzoom" alt="...">
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
                      </div>
                    </b-col>
                    <b-col cols="12" sm="12" md="12" lg="6" xl="6">
                      <div>
                        <div class="card">
                          <img src="https://i.imgur.com/CdVCi8i.png" class="card-img-top imgzoom" alt="...">
                          <br>
                          <div class="card-body">
                            <h5 class="card-title"><i class="fa fa-location-arrow" aria-hidden="true"></i> {{titleOO}}</h5>
                            <p class="card-text">{{detailOO}}</p><br><br>
                            <!-- <p class="card-text"><small class="text-muted">Last updated 3 mins ago</small></p> -->
                            <div class="align-right">
                              <button class="button"><a class="linkmap" target="_blank" v-bind:href="linkOO"><img style="width:50px;height:50px;" src="https://i.imgur.com/JKjVDrz.png" alt=""></a></button>
                            </div>
                          </div>
                        </div>
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
      titleOA: 'Office address',
      titleOO: 'Operational Office',
      detailOA: '55/39/1 Mhutee 13 Navanakorn Phahoyothin Road, Klong Nueng, Klong Luang, Patumtanee Thailand 12120',
      detailOO: '19/125 Soi Sukhumvit 13, Klong Toey Nua, Wattana, Bangkok 10110, Thailand',
      linkOA: '#',
      linkOO: 'https://www.google.co.th/maps/place/LOGIPROTECH+(THAILAND)+CO.,LTD./@13.7428174,100.5554025,17z/data=!3m1!4b1!4m5!3m4!1s0x30e29f468d5f8f5b:0x2085bde87d87f06b!8m2!3d13.7428122!4d100.5575912?hl=th'
    }
  }

}
</script>
<style scoped src="@/assets/css/contact.css">

</style>
