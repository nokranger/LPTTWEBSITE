<template>
  <div>
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
  created () {
    document.title = 'Home LPTT - LPTT'
  }
}
</script>
