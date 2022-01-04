<template>
  <div class="section border-bottom border-dark pt-4 pb-5">
    <div class="content container px-4">
      <div class="row">
        <div class="col-lg-6 col-xl-6 col-12 col-sm-6">
          <AboutUs />
        </div>
        <div class="col-lg-6 col-xl-6 col-12 col-sm-6">
          <WhyUs />
        </div>
      </div>
      <div class="row">
        <div class="col-12">
          <Travel />
          <Button />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
// @ is an alias to /src
import AboutUs from '@/components/AboutUs.vue'
import WhyUs from '@/components/WhyUs.vue'
import Travel from '@/components/Travel.vue'
import Button from '@/components/Button.vue'


export default {
  name: 'Section3',
  components: {
    AboutUs,
    WhyUs,
    Travel,
    Button,
  }
}
</script>

<style scoped lang="scss">
.section {
  background-color: rgb(197, 239, 252);
}
</style>

