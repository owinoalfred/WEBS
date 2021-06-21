<template>
<div>
  <div class="home mb-1">
  <Upper />
  <Navy />
  <Bodydata />
  
  <Lowerbody />
  <Footer />
  </div>
  </div>
</template>

<script>
// @ is an alias to /src
import Bodydata from '@/components/Bodydata.vue'
import Footer from '@/components/Footer.vue'
import Lowerbody from '@/components/Lowerbody.vue'
import Navy from '@/components/Navy.vue'
import Upper from '@/components/Upper.vue'

export default {
  name: 'Home',
  components: {
    Bodydata,
    Footer,
    Navy,
    Lowerbody,
    Upper
  }
}
</script>
