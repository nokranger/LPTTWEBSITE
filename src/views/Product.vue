<template>
  <div>
    <div class="partner-section">
      <div class="container-wrapper">
        <div class="container-partner">
          <div class="container-partner-title">
          </div>
          <div>
            <service></service>
            <div class="align-center"><h1>Products</h1></div><br>
            <!-- <div class="align-center"><h1>Ubisense™ Products</h1></div><br> -->
            <b-container class="align-center">
                <b-row>
                  <b-col cols="12" sm="12" md="12" lg="4" xl="4">
                    <div class="card mb-3">
                    <img v-b-modal.modal-lgd4 style="width:100%;hieght:auto;" src="https://i.imgur.com/TnQliMa.jpg" class="card-img-top" alt="...">
                      <div class="card-body">
                        <h5 class="card-title">Dimension4 Sensor Systems</h5>
                        <p class="card-text spaced" style="text-overflow: ellipsis;overflow: hidden;white-space: nowrap;">{{dSensor}}</p>
                      </div>
                      <b-modal hide-footer id="modal-lgd4" size="lg">
                        <div class="card mb-3">
                          <img style="width:100%;hieght:auto;" src="https://i.imgur.com/TnQliMa.jpg" class="card-img-top" alt="...">
                          <div class="card-body">
                            <h5 class="card-title">Dimension4 Sensor Systems</h5>
                            <p class="card-text spaced">{{dSensor}}</p>
                          </div>
                        </div>
                      </b-modal>
                    </div>
                  </b-col>
                  <b-col cols="12" sm="12" md="12" lg="4" xl="4">
                    <div class="card mb-3">
                      <img v-b-modal.modal-lgtag style="width:100%;hieght:auto;" src="@/assets/img/tag1_new.jpg" class="card-img-top" alt="...">
                      <div class="card-body"><br><br>
                        <h5 class="card-title" style="margin-top:7px;">TAG</h5><br>
                        <p class="card-text spaced" style="text-overflow: ellipsis;overflow: hidden;white-space: nowrap;">{{dTAG}}</p>
                      </div>
                      <b-modal hide-footer id="modal-lgtag" size="lg">
                        <div class="card mb-3">
                          <img style="width:100%;hieght:auto;" src="@/assets/img/tag1_new.jpg" class="card-img-top" alt="...">
                          <div class="card-body">
                            <h5 class="card-title">TAG</h5>
                            <p class="card-text spaced">{{dTAG}}</p>
                          </div>
                        </div>
                      </b-modal>
                    </div>
                  </b-col>
                  <b-col cols="12" sm="12" md="12" lg="4" xl="4">
                    <div class="card mb-3">
                      <img v-b-modal.modal-lguss style="width:100%;hieght:auto; !important" src="@/assets/img/smartspace_new.png" class="card-img-top" alt="...">
                      <div class="card-body"><br>
                        <h5 class="card-title">Ubisense SmartSpace™ Platform</h5>
                        <p class="card-text spaced" style="text-overflow: ellipsis;overflow: hidden;white-space: nowrap;">{{dSmartSpace}}</p>
                        <!-- <p class="card-text" style="text-overflow: ellipsis;overflow: hidden;white-space: nowrap;">{{dSmartSpace2}}</p> -->
                      </div>
                      <b-modal hide-footer id="modal-lguss" size="lg">
                        <div class="card mb-3">
                          <img style="width:100%;hieght:auto; !important" src="@/assets/img/smartspace_new.png" class="card-img-top" alt="...">
                          <div class="card-body">
                            <h5 class="card-title">Ubisense SmartSpace™ Platform</h5>
                            <p class="card-text spaced">{{dSmartSpace}}</p>
                            <p class="card-text">{{dSmartSpace2}}</p>
                          </div>
                        </div>
                      </b-modal>
                    </div>
                  </b-col>
                </b-row>
                <br>
            </b-container>
            <!-- <div class="align-left">
              <div class="card mb-3">
                <img style="width:100%;hieght:auto;" src="https://i.imgur.com/TnQliMa.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Dimension4 Sensor Systems</h5>
                  <p class="card-text spaced">{{dSensor}}</p>
                </div>
              </div>
              <div class="card mb-3">
                <img style="width:100%;hieght:auto;" src="@/assets/img/tag1.jpg" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">TAG</h5>
                  <p class="card-text spaced">{{dTAG}}</p>
                </div>
              </div>
              <div class="card mb-3">
                <img style="width:100%;hieght:auto; !important" src="https://i.imgur.com/l78uXYX.png" class="card-img-top" alt="...">
                <div class="card-body">
                  <h5 class="card-title">Ubisense SmartSpace™ Platform</h5>
                  <p class="card-text spaced">{{dSmartSpace}}</p>
                  <p class="card-text">{{dSmartSpace2}}</p>
                </div>
              </div>
            </div> -->
          </div>
          <br>
        </div>
      </div>
    </div>
    <!-- <service></service> -->
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
      dSensor: 'Ubisense Dimension4 Sensor Systems (RTLS: Real-Time Location Services)Dimension4 sensors are first-class Ethernet connected devices powered over Ethernet (POE) that can be deployed both indoors and outdoors (using appropriate Ingress Protection options). With industry-leading Ultra-Wide Band (UWB) location sensor systems that uses both Angle of Arrival (AoA) and Time Distance of Arrival (TDoA) technology for unparalleled levels of accuracy, reliability and scale.',
      dTAG: 'Ubisense tags offer industrially-proven reliability and cover a range of tracking and application needs. Tag variants offer different combinations of battery lifetime, Ingress Protection, robustness and even location modalities (including GPS).',
      dSmartSpace: 'The SmartSpace™ modular software platform uses real-time location and identification data from multiple sources to deliver a real-time digital twin of our customer’s physical operations, proven to drive quality, increase productivity, manage complexity and reduce costs.The SmartSpace™ modular software platform uses real-time location and identification data from multiple sources and creates a real-time digital twin of your physical environment, using the best location-sensing technology and gives you the power to easily analyze, error-proof and automated processes proven to drive quality, increase productivity, manage complexity and reduce costs.',
      dSmartSpace2: '< LPTT is the Sole distributor of Ubisense Products for South East Asia Region >'
    }
  },
  created () {
    document.title = 'Product and Service LPTT - LPTT'
  }
}
</script>
<style scoped src="@/assets/css/product.css">

</style>
