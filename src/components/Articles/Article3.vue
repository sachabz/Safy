<template>
  <div class="card article border-0">
    <div class="card-body m-">
      <div class="card-title row pt-2 pb-3">
        <div class="col-3">
          <img src="../../assets/12.png" />
        </div>
        <div class="col-9">
          <h5 class="title mt-2">Meet new people and live more intensely</h5>
        </div>
      </div>

      <p
        class="card-text p-0"
      >Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
      <a href="#" class="text-danger">more info</a>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Article',
  props: {

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
