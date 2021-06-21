<template>
    <div>
    <Upper />
<Navy />
<Teams />
<Footer />
    </div>

</template>
<script>
import Footer from '@/components/Footer.vue'

import Navy from '@/components/Navy.vue'
import Upper from '@/components/Upper.vue'
import Teams from '@/components/Teams.vue'

export default {
  components: {
    Footer,
    Navy,
    Upper,
	Teams
  }

}
</script>