<template>
  <div>
    <div>
      <b-navbar toggleable="lg" variant="light">
        <b-navbar-brand href="#" class="ml-5 pl-5">Dorti</b-navbar-brand>

        <b-collapse id="nav-collapse" is-nav>
          <b-navbar-nav class="ml-5 pl-5 pt-3 text-center" center>
            <div class="d-flex ml-5 pl-5">
              <div class="p-3 ml-5 pl-5">
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
            </div>
          </b-navbar-nav>

          <!-- Right aligned nav items -->
          <b-navbar-nav class="ml-auto">
            <div right class="d-flex">
              <div class="p-3 mt-2">
                <router-link to="/signup">
                  <p>Sign In</p>
                </router-link>
              </div>
              <div class="p-3">
                <router-link to="/login">
                  <b-button id="btn">Login</b-button>
                </router-link>
              </div>
            </div>
          </b-navbar-nav>
        </b-collapse>
      </b-navbar>
    </div>
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
a:hover{
  text-decoration: none;
  color: #2c3e50;
}
</style>
