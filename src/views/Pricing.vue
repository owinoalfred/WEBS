<template>
    <div>
    <Upper />
<Navy />
<Prices />
<Footer />
    </div>

</template>
<script>
import Footer from '@/components/Footer.vue'
import Prices from '@/components/Prices.vue'
import Navy from '@/components/Navy.vue'
import Upper from '@/components/Upper.vue'

export default {
  components: {
    Footer,
    Navy,
    Prices,
    Upper
  }

}
</script>