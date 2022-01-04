<template>
  <div class="container">
    <div class="row">
      <div class="col-lg-4 col-xl-4 col-12 col-sm-4 p-0 m-0">
        <Article />
      </div>
      <div class="col-lg-4 col-xl-4 col-12 col-sm-4 p-0 m-0">
        <Article2 />
      </div>
      <div class="col-lg-4 col-xl-4 col-12 col-sm-4 p-0 m-0">
        <Article3 />
      </div>
    </div>
  </div>
</template>

<script>
import Article from '@/components/Articles/Article.vue'
import Article2 from '@/components/Articles/Article2.vue'
import Article3 from '@/components/Articles/Article3.vue'
export default {
  name: 'Articles',
  components: {
    Article,
    Article2,
    Article3,
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.card-title {
  background-color: #8c77ff;
  color: whitesmoke;
}
</style>
