<template>
  <div>
    <div class="partner-section">
      <div class="container-wrapper">
        <div class="container-partner">
          <div class="container-partner-title">
          </div>
            <div>
                <div class="align-center"><h1>{{title}}</h1></div>
                <div>
                  <p>
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
      detailLptt: 'Logiprotech (Thailand) Co., Ltd. (LPTT) is an Internet of Thing Accelerator company with our main focus is to add values to the client’s operation control. Though we are a newly established, we are striving to become one of the leading Industrial Internets of Thing solution providers. With our production control and logistic management expertise and by applying the precise tracking technology device platform and other internets of thing (IOT), we are able to improve the operation effectiveness of our customer.'
    }
  }

}
</script>
<style scoped src="@/assets/css/article.css">

</style>
