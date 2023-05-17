<template>
  <div class="about">
    <AboutUs msg="About DFS"/>
  </div>
</template>

<script>
// @ is an alias to /src
import AboutUs from '@/components/AboutUs.vue'

export default {
  name: 'About',
  components: {
    AboutUs
  }
}
</script>