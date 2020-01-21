<template>
  <div>
    <div class="partner-section">
      <div class="container-wrapper">
        <div class="container-partner">
          <div class="container-partner-title">
          </div>
            <div>
              <p class="align-left spaced qout">
                "{{qout}}"
              </p>
                <div class="align-center"><h1>{{titleLpt}}</h1></div><br>
                <div>
                  <p class="align-left spaced" style="margin:10px;">
                    {{detailLpt}}
                  </p>
                </div>
            </div>
            <div>
                <div class="align-center"><h1>{{titleLptt}}</h1></div><br>
                <div>
                  <p class="align-left spaced" style="margin:10px;">
                    {{detailLptt}}
                  </p>
                </div>
                <br>
                <div>
                  <p class="align-left spaced" style="margin:10px;">
                    {{detailLptt2}}
                  </p>
                </div>
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
      qout: 'IOT is the most renown talked-about topics in the tech industry community and approximately 20 billion devices are predicted to be used in the next 5 years. Companies in all regions are vying to align themselves with the technology to create a new business potential.',
      titleLpt: 'Logiprotech (LPT)',
      detailLpt: 'Logiprotech (LPT) was founded in Japan in October 2015. It has been successfully deploying IOT applications based on TPS concept to help dramatically improve production and logistic operations.',
      titleLptt: 'Logiprotech Thailand (LPTT)',
      detailLptt: 'Logiprotech (Thailand) was established in June 2017 to serve our customers in Thailand and neighbouring region.',
      detailLptt2: 'Logiprotech (Thailand) Co., Ltd. (LPTT) is an IOT Accelerator company. Our main focus is to add values to the client’s operation control. With our expertise in production control and logistic management as well as the precise tracking technology device platform (Real-Time Location Services (RTLS) technology) and other internet of things (IOT), we are aiming to achieve breakthrough improvement for our customers in production and logistic operations.'
    }
  },
  created () {
    document.title = 'About LPTT - LPTT'
  }

}
</script>
<style scoped src="@/assets/css/about.css">

</style>
