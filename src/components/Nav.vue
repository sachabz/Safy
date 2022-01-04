<template>
  <nav
    class="navbar navbar-expand-lg navbar-light border-bottom border-top border-dark px-0 mx-0 mt-4 mb-4"
    style="background-color: #8c77ff;"
  >
    <div class="container-fluid mx-4">
      <div class="container">
        <a class="navbar-brand" href="#">
          <img src="../assets/18.jpg.png" height="100" />
        </a>
      </div>
      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav">
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Home</a>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              id="navbarDropdownMenuLink"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >Book</a>
          </li>
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle"
              href="#"
              id="navbarDropdownMenuLink"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >Destinations</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Prices</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Alert</a>
          </li>
          <li class="nav-item">
            <a class="nav-link active" aria-current="page" href="#">Contact</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
</template>

<script>
export default {
  name: 'Nav',
  components: {

  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.navbar-nav {
  text-align: center;
  justify-content: center;
}

.navbar-brand {
  justify-content: center;
}
</style>
