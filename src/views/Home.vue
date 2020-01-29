<template>
  <div>
    <meta name="google-site-verification" content="hj-sZSDyD7lXYy51Tj5j2-JBsYZf-3FLY5hj3dUyPaY" />
    <meta name="keywords" content="Lptt company website, lptt website, iot, smart factory, RTLS (Real-Time Location Services) Smart Factory, RTLS,real time location systems, rfid solution, rfid, business process design system architect">
    <l-article></l-article>
    <partner></partner>
  </div>
</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Article from './Article'
import Partner from './Partner'

export default {
  name: 'home',
  components: {
    // HelloWorld,
    'l-article': Article,
    'partner': Partner
  },
  metaInfo () {
    return {
      title: 'Home LPTT - LPTT',
      meta: [
        {
          name: 'description',
          content: 'Lptt company website, lptt website, iot, smart factory, RTLS (Real-Time Location Services) Smart Factory, RTLS,real time location systems, rfid solution, rfid, business process design system architect'
        },
        {
          name: 'keywords',
          content: 'Lptt company website, lptt website, iot, smart factory, RTLS (Real-Time Location Services) Smart Factory, RTLS,real time location systems, rfid solution, rfid, business process design system architect'
        },
        {
          name: 'google-site-verification',
          content: 'hj-sZSDyD7lXYy51Tj5j2-JBsYZf-3FLY5hj3dUyPaY'
        }
      ]
    }
  }
  // created () {
  //   document.title = 'Home LPTT - LPTT'
  // }
}
</script>
