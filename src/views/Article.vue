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
      detailLptt: 'Logiprotech (Thailand) Co., Ltd. (LPTT) is an Internet of Thing Accelerator company. Our main focus is to add values to the client’s operation control. With our expertise in production control and logistic management and applying the precise tracking technology device platform　(Ubisense Real-Time Location Services (RTLS) technology)　and other internets of thing (IOT), we able to improve the operation effectiveness of our customer.Though LPTT is a newly established　Company, we are striving to become one of the leading Industrial Internets of Thing solution providers.'
    }
  }

}
</script>
<style scoped src="@/assets/css/article.css">

</style>
