<template>
  <div>
    <navBar />

    <div class="row mt-4">
      <div id="bar" class="col-3 py-3">
        <div class="px-4 py-2">
          <div class="dashboard d-flex text-white p-3">
            <b-icon class="h2" icon="grid1x2"></b-icon>
            <div class="ml-3 mt-1">
              <h5>Dashboard</h5>
            </div>
          </div>
        </div>
        <div class="px-4 py-2">
          <div class="user d-flex p-3">
            <b-icon class="h2" icon="person"></b-icon>
            <div class="ml-3 mt-1">
              <h5>Profile</h5>
            </div>
          </div>
        </div>
        <div class="px-4 py-2">
          <div class="user d-flex p-3">
            <b-icon class="h2" icon="wallet"></b-icon>
            <div class="ml-3 mt-1">
              <h5>Wallet</h5>
            </div>
          </div>
        </div>
        <div class="px-4 py-2">
          <div class="user d-flex p-3">
            <b-icon class="h2" icon="bell"></b-icon>
            <div class="ml-3 mt-1">
              <h5>Notification</h5>
            </div>
          </div>
        </div>
        <div class="px-4 py-2">
          <div class="user d-flex p-3">
            <b-icon class="h2" icon="gear"></b-icon>
            <div class="ml-3 mt-1">
              <h5>Settings</h5>
            </div>
          </div>
        </div>
      </div>
      <div id="bar" class="col-5 mx-5">
        <div class="m-5 text-left">
          <h5>Post a dorti</h5>
          <div>
            <b-card class="mb-2 text-center">
              <b-icon class="h1" icon="upload"></b-icon>
              <b-card-text> Upload a picture</b-card-text>
            </b-card>
          </div>
          <div class="px-4 py-2">
            <div class="user d-flex p-3">
              <div class="ml-3 mt-1">
                <h5>Add Location</h5>
              </div>
            </div>
          </div>
          <div class="px-4 py-2">
            <div class="user d-flex p-3">
              <div class="ml-3 mt-1">
                <h5>Comment</h5>
              </div>
            </div>
          </div>
          <div class="px-4 py-2">
            <div class="user d-flex p-3">
              <div class="ml-3 mt-1">
                <h5>Type of dorti</h5>
              </div>
            </div>
          </div>
          <div class="text-right mt-3">
            <input id="button" type="button" value="Post" />
          </div>
        </div>
      </div>
      <div id="bar" class="col-3">
        <div class="px-4 py-2">
          <div class="text-left">
            <p>Top Earners for this week</p>
            <p id="small">Today 23rd January 2020</p>
          </div>
          <div class="user d-flex p-3">
            <div class="d-flex">
              <img id="img" src="../assets/emmy.png" alt="" />
              <div>
                <h6>Oluwabunmi Oje</h6>
                <span class="ml-2" id="small">Agreey Road, Port Harcourt</span>
              </div>
              <div class="d-flex">
                <p>20</p>
                <b-icon class="h5" variant="warning" icon="star"></b-icon>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>


<script>
import navBar from "./navBar";
export default {
  components: {
    navBar,
  },
};
</script>
<style scoped>
#bar {
  box-shadow: 0 4px 8px 0 rgba(131, 130, 130, 0.2), 0 6px 20px 0 rgba(94, 93, 93, 0.19);
}
.dashboard {
  background-color: rgba(78, 54, 146, 1);
  border-radius: 10px;
}
.user {
  box-shadow: 0 4px 8px 0 rgba(131, 130, 130, 0.2), 0 6px 20px 0 rgba(94, 93, 93, 0.19);
  border-radius: 10px;
}
#button {
  padding: 10px;
  width: 100px;
  border-radius: 10px;
  background-color: white;
  border: 1px solid rgba(78, 54, 146, 1);
}
#small {
  font-size: 12px;
  color: rgb(170, 165, 165);
  margin-top: -15px;
}
#img {
  height: 40px;
}
</style>
