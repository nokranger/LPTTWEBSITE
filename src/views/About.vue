<template>
  <div>
    <div class="partner-section">
      <div class="container-wrapper">
        <div class="container-partner">
          <div class="container-partner-title">
          </div>
            <div>
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
      titleLpt: 'Logiprotech (LPT)',
      detailLpt: 'first began its operation in Japan in October 2015. Thanks, an IOT, the most renown talked-about topics in the tech industry community and with approximately 20 billion devices predicted in the next 5 years, there are high commercial possibilities. Companies all over the region are vying to align themselves with the technology to create a new business potential. As such',
      titleLptt: 'Logiprotech (Thailand)',
      detailLptt: 'have been established in June 2018, to serve as the regional office to service our customer in Thailand and neighbor region.',
      detailLptt2: 'Logiprotech (Thailand) Co., Ltd. (LPTT) is an Internet of Thing Accelerator company. Our main focus is to add values to the client’s operation control. With our expertise in production control and logistic management and applying the precise tracking technology device platform　(Ubisense Real-Time Location Services (RTLS) technology)　and other internets of thing (IOT), we able to improve the operation effectiveness of our customer.Though LPTT is a newly established　Company, we are striving to become one of the leading Industrial Internets of Thing solution providers.'
    }
  },
  created () {
    document.title = 'About LPTT - LPTT'
  }

}
</script>
<style scoped src="@/assets/css/about.css">

</style>
