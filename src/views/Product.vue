<template>
  <div>
    <div class="partner-section">
      <div class="container-wrapper">
        <div class="container-partner">
          <div class="container-partner-title">
          </div>
          <div>
            <div class="align-center"><h1>PRODUCT</h1></div>
            <div class="align-left">
              <ul class="product">
                <li class="align-center"><b>SENSORS</b><br>
                  <img class="imgzoom" src="@/assets/img/sensor1.jpg" style="width:300px;hieght:300px;margin:10px;" alt="">
                  <ul>{{dSensor}}</ul>
                </li>
                <li class="align-center"><b>TAG</b><br>
                  <img class="imgzoom" src="@/assets/img/tag1.jpg" style="width:300px;hieght:300px;margin:10px;" alt="">
                  <ul>{{dTAG}}</ul>
                </li>
              </ul>
            </div>
          </div>
          <br>
        </div>
      </div>
    </div>
    <service></service>
  </div>
</template>
<script>
import Service from './Services'
export default {
  components: {
    'service': Service
  },
  data () {
    return {
      dSensor: 'Dimension4 sensors are first-class Ethernet connected devices powered over Ethernet (POE) that can be deployed both indoors and outdoors (using appropriate Ingress Protection options).Dimension4 sensors are precision ultrawideband (UWB) measurement devices, hosting an array of antennas and ultra-wideband radio receivers for best-in-class detection and localization of Ubisense UWB tags.',
      dTAG: 'Ubisense tags offer industrially-proven reliability and cover a range of tracking and application needs. Tag variants offer different combinations of battery lifetime, Ingress Protection, robustness and even location modalities (including GPS).'
    }
  }
}
</script>
<style scoped src="@/assets/css/product.css">

</style>
