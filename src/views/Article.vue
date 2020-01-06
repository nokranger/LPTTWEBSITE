<template>
  <div class="article">
    <div class="detailArticle">
      <div style="padding-top: 350px;">
        <h1>{{title}}</h1>
        <div>
          <p style="margin:5px;">{{detailLptt}}</p>
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
