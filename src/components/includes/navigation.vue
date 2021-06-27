<template>
  <div class="navigation">
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="container">
        <a class="navbar-brand" href="#">
          <img
            src="../../assets/images/logo-text.png"
            alt="logo-text"
            class="img-fluid"
            width="150px"
          />
        </a>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarSupportedContent"
          aria-controls="navbarSupportedContent"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarSupportedContent">
          <ul class="navbar-nav mr-auto">
            <!-- <li class="nav-item active">
            <a class="nav-link" href="#"
              >Home <span class="sr-only">(current)</span></a
            >
          </li> -->
            <!-- <li class="nav-item">
            <a class="nav-link" href="#">About</a>
          </li> -->
          </ul>
          <router-link
            to="/login"
            class="btn btn-outline-success btn-outline-red my-2 my-sm-0"
            type="submit"
          >
            Login
          </router-link>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.btn-outline-red {
  border-color: #ff1e12;
  color: #ff1e12;
}

.btn-outline-red:hover {
  color: #fff;
  background-color: #ff1e12;
  border-color: #ff1e12;
}
</style>
