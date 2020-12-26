<template>
  <div>
    <nav class="navbar navbar-expand-lg navbar-light bg-light">
      <div class="ml-lg-5 pl-lg-5 mr-lg-5 pr-lg-5">
        <img src="../assets/logo.svg" alt="" />
      </div>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNavAltMarkup"
        aria-controls="navbarNavAltMarkup"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
        <div class="navbar-nav ml-lg-5 pl-lg-5 pt-lg-4 text-center">
          <div class="p-3 ml-lg-5">
            <router-link to="/">
              <p>Dorti</p>
            </router-link>
          </div>
          <div class="p-3">
            <p>Curretnt Trending</p>
          </div>
          <div class="p-3">
            <p>Achievements</p>
          </div>
          <div right class="d-flex ml-lg-5 pl-5">
            <div class="p-3 ml-5 pl-5">
              <router-link to="/signup">
                <p>Sign In</p>
              </router-link>
            </div>
          </div>
        </div>
      </div>
    </nav>

    
  </div>
</template>
<script>
export default {};
</script>
<style scoped>
#btn {
  background-color: rgba(78, 54, 146, 1);
  width: 120%;
  padding: 10px;
  border-radius: 8px;
}
.navbar-expand-lg {
  height: 60px !important;
}
a {
  text-decoration: none;
  color: #2c3e50;
}
a:hover {
  text-decoration: none;
  color: #2c3e50;
}
</style>
