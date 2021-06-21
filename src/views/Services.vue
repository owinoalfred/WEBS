<template>
<div>
   <Upper />
    <Navy />
    <h1>
        Services coming soon
    </h1>
    <Footer />
</div>

</template>
<script>
import Footer from '@/components/Footer.vue'
import Navy from '@/components/Navy.vue'
import Upper from '@/components/Upper.vue'

export default {
    name: 'Services',
    components: {
        Footer,
        Navy,
        Upper  }
}
</script>