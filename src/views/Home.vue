<template>
  <div class="home m-0 p-0">
    <Section1 />
    <Section2 />
    <Section3 />
    <Section4 />
  </div>
</template>

<script>
// @ is an alias to /src
import Section1 from './Section1.vue'
import Section2 from './Section2.vue'
import Section3 from './Section3.vue'
import Section4 from './Section4.vue'

export default {
  name: 'Home',
  components: {
    Section1,
    Section2,
    Section3,
    Section4,
  }
}
</script>

<style scoped lang="scss">
.section1 {
  background-color: rgb(197, 239, 252);
}
</style>

