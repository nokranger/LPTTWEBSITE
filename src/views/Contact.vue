<template>
  <div>
    <div class="partner-section">
      <div class="container-wrapper">
        <div class="container-partner">
          <div class="container-partner-title">
          </div>
            <div>
                <div class="align-center"><h1>CONTACT</h1></div>
                <div class="align-left">
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
                        <li>{{titleAO}}
                            <ul class="address">{{detailAO}}
                                <li class="align-center"><button><a target="_blank" v-bind:href="linkAO">View Google Map</a></button></li>
                            </ul>
                        </li>
                    </ul>
                </div>
                <b-container>
                <b-row>
                    <b-col cols="6" sm="6" md="6" lg="6" xl="6"><a href="tel:029090320"><img class="imgzoom" style="border-radius: 20%;width:100px;height:100px;" src="https://i.imgur.com/IR9SwSq.jpg" alt=""></a></b-col>
                    <b-col cols="6" sm="6" md="6" lg="6" xl="6"><a href="mailto:info@logiprotech-th.co.th"><img class="imgzoom" style="border-radius: 20%;width:100px;height:100px;" src="https://i.imgur.com/yQK7Dyc.png" alt=""></a></b-col>
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
      titleAO: 'Administrative Office',
      detailOA: '55/39/1 Mhutee 13 Navanakorn Phahoyothin Road, Klong Nueng, Klong Luang, Patumtanee Thailand 12120',
      detailOO: '19/125 Soi Sukhumvit 13, Klong Toey Nua, Wattana, Bangkok 10110, Thailand',
      detailAO: '55/39/1 Mhutee 13 Navanakorn Phahoyothin Road, Klong Nueng, Klong Luang, Patumtanee Thailand 12120',
      linkOA: 'https://www.google.co.th/maps/place/LOGIPROTECH+(THAILAND)+CO.,LTD./@13.7428174,100.5554025,17z/data=!3m1!4b1!4m5!3m4!1s0x30e29f468d5f8f5b:0x2085bde87d87f06b!8m2!3d13.7428122!4d100.5575912?hl=th',
      linkOO: '#',
      linkAO: '#'
    }
  }

}
</script>
<style scoped src="@/assets/css/contact.css">

</style>
