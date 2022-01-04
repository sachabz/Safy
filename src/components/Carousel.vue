<template>
  <div id="carouselExampleIndicators" class="carousel slide container pb-4" data-ride="carousel">
    <ol class="carousel-indicators">
      <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="4"></li>
      <li data-target="#carouselExampleIndicators" data-slide-to="5"></li>
    </ol>
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img class="d-block w-100" src="../assets/6.jpg" alt="First slide" />
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="../assets/7.jpg" alt="Second slide" />
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="../assets/8.jpg" alt="Third slide" />
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="../assets/9.jpg" alt="Fourth slide" />
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="../assets/10.jpg" alt="Fourth slide" />
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="../assets/11.jpg" alt="Fourth slide" />
      </div>
    </div>
    <a
      class="carousel-control-prev rounded-circle .bg-dark.bg-gradient"
      href="#carouselExampleIndicators"
      role="button"
      data-slide="prev"
    >
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a
      class="carousel-control-next"
      href="#carouselExampleIndicators"
      role="button"
      data-slide="next"
    >
      <span class="carousel-control-next-icon rounded-circle" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</template>

<script>
export default {
  name: 'Carousel',
  props: {

  }
}

</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
</style>
