<template>
  <div class="register">
    <div class="container">
      <div class="row card shadow d-flex flex-row align-items-center">
        <div class="col-lg-6 p-5">
          <ChattyLogo />
          <!-- <p class="chattyfoodies">
            Food and conversation is Life and experiences should be shared with
            friends and family.
          </p> -->
        </div>
        <div class="col-lg-6">
          <main class="d-flex flex-column align-items-stretch p-4">
            <h2 class="mb-5">Create your account</h2>
            <form>
              <div class="form-group">
                <input
                  type="text"
                  class="form-control"
                  id="name"
                  aria-describedby="emailHelp"
                  placeholder="Full Name"
                />
              </div>
              <div class="form-group">
                <label for="exampleInputEmail1">Gender</label>
                <select class="form-control">
                  <option>Male</option>
                  <option>Female</option>
                </select>
              </div>
              <div class="form-group">
                <label for="exampleInputEmail1">Account Type</label>
                <select class="form-control">
                  <option>User</option>
                  <option>Business</option>
                </select>
              </div>
              <div class="form-group">
                <input
                  type="email"
                  class="form-control"
                  id="exampleInputEmail1"
                  aria-describedby="emailHelp"
                  placeholder="Email"
                />
              </div>
              <div class="form-group">
                <input
                  type="password"
                  class="form-control"
                  id="exampleInputPassword1"
                  placeholder="Password"
                />
              </div>

              <button
                type="submit"
                class="btn btn-primary btn-block btn-register mb-4"
              >
                Register
              </button>

              <p>
                Already have an account?
                <router-link to="/login">Login</router-link>
              </p>
            </form>
          </main>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import ChattyLogo from "@/components/ChattyLogo";
export default {
  name: "Register",
  components: {
    ChattyLogo,
  },
};
</script>

<style scoped>
.btn-register {
  background-color: black;
  border-color: black;
}

p.chattyfoodies {
  margin-top: 25px;
  font-size: 1.25rem;
}
</style>
