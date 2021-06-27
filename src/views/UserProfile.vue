<template>
  <div class="user-profile">
    <MainNavigation />
    <UserBgCover />
    <div class="container">
      <div class="row">
        <div class="col-lg-3">
          <Sidebar />
        </div>
        <div class="col-lg-6">User Feed</div>
        <div class="col-lg-3">Photos & Vedios</div>
      </div>
    </div>
  </div>
</template>

<script>
import MainNavigation from "@/components/includes/main-navigation";
import UserBgCover from "@/components/UserBgCover";
import Sidebar from "@/components/includes/Sidebar";
export default {
  name: "UserProfile",
  components: {
    MainNavigation,
    UserBgCover,
    Sidebar,
  },
};
</script>

<style scoped>
.user-profile {
  border: 1px solid red;
}
</style>
