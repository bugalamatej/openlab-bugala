<template>
  <div class="container">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container-fluid">
        <img
          src="https://openlab.sk/wp-content/themes/wp-bootstrap-starter/assets/images/openlab-logo.svg"
          alt=""
          class="navbar-brand ml-5"
        />
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav me-auto mb-2 mb-lg-0">
            <li class="nav-item">
              <a class="nav-link blue-hover" aria-current="page" href="#"
                >Úvod</a
              >
            </li>
            <li class="nav-item dropdown">
              <a
                class="blue-hover nav-link dropdown-toggle"
                href="#"
                id="navbarDropdown"
                role="button"
                data-bs-toggle="dropdown"
                aria-expanded="false"
              >
                Openlab
              </a>
              <ul class="dropdown-menu" aria-labelledby="navbarDropdown">
                <li>
                  <a class="blue-hover dropdown-item" href="#">HybriLab</a>
                </li>
                <li>
                  <a class="blue-hover dropdown-item" href="#">GamesLab</a>
                </li>
                <li>
                  <a class="blue-hover dropdown-item" href="#">AppsLab</a>
                </li>
              </ul>
            </li>
            <li class="nav-item">
              <a class="blue-hover nav-link" href="#">Pre učiteľov</a>
            </li>

            <li class="nav-item">
              <a class="nav-link blue-hover" href="#">Partneri</a>
            </li>
            <li class="nav-item">
              <a class="nav-link blue-hover" href="#">Moderná škola</a>
            </li>
          </ul>

          <button class="btn btn-primary blue" type="submit">
            Pridajte sa k nám
          </button>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "HelloWorld",
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->

<style scoped>
.navbar {
  height: 100px;
  background-color: white !important;
}

.blue {
  background-color: #3597ff !important;
}
.blue-hover:hover {
  color: #3597ff !important;
}

.outline-menu {
  border: 0px solid red !important;
  outline: none !important;
  box-shadow: none !important;
}

.dropdown-menu {
  border: none;
}

.dropdown-item:hover {
  background-color: white !important;
}

.btn{
    border: none !important;
    padding: 12px 20px;
    border-radius: 6px;
}
</style>
