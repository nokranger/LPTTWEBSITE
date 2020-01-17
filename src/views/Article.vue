<template>
  <div>
    <div class="partner-section">
      <div class="container-wrapper">
        <div class="container-partner">
          <div class="container-partner-title">
          </div>
            <div>
                <div class="align-center"><h1>{{title}}</h1></div><br>
                <div>
                  <p class="align-left spaced" style="margin:10px;margin-top:-10px;">
                    {{detailLptt}}
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
      title: 'Grow your business with LPTT',
      detailLptt: 'Logiprotech (Thailand) Co., Ltd. (LPTT) is an IOT Accelerator company. Our main focus is to add values to the client’s operation control. With our expertise in production control and logistic management as well as the precise tracking technology device platform　(Real-Time Location Services (RTLS) technology) and other internet of things (IOT), we are aiming to achieve breakthrough improvement for our customers in production and logistic operations.'
    }
  }

}
</script>
<style scoped src="@/assets/css/article.css">

</style>
