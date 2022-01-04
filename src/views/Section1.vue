<template>
  <div class="section border-bottom border-dark text-center">
    <div class="content container px-4">
      <Icon />
    </div>
    <div class="content">
      <Nav />
    </div>
    <div class="content container px-4">
      <Carousel />
    </div>
    <img src="../assets/button.png" class="rounded mx-auto d-block pb-3" />
  </div>
</template>

<script>
// @ is an alias to /src
import Icon from '@/components/Icon.vue'
import Nav from '@/components/Nav.vue'
import Carousel from '@/components/Carousel.vue'

export default {
  name: 'Section1',
  components: {
    Icon,
    Nav,
    Carousel,
  }
}
</script>

<style scoped lang="scss">
.section {
  background-color: rgb(197, 239, 252);
}
</style>

