<template>
  <div class="login">
    <div class="container">
      <div class="row">
        <div
          class="card-content card shadow card-login d-flex flex-row w-100 mt-5"
        >
          <div class="col-lg-6 p-5">
            <ChattyLogo />
          </div>
          <div class="col-lg-6">
            <main class="d-flex flex-column align-items-stretch p-4">
              <h2 class="mb-5">Login to your account</h2>
              <form>
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

                <div class="d-flex justify-content-between">
                  <div class="form-group form-check">
                    <input
                      type="checkbox"
                      class="form-check-input"
                      id="exampleCheck1"
                    />
                    <label class="form-check-label" for="exampleCheck1"
                      >Remmeber me
                    </label>
                  </div>

                  <a href="#">Forgot Password?</a>
                </div>
                <router-link
                  to="/user-profile"
                  type="submit"
                  class="btn btn-primary btn-block btn-login mb-4"
                >
                  Login
                </router-link>
              </form>
              <p>
                Don't have an account?
                <router-link to="/register">Register here</router-link>
              </p>
              <twitter-button
                shareUrl="https://github.com/"
                shareDescription="GitHub is where people build software."
              />
              <facebook-button
                shareUrl="https://github.com/"
                shareDescription="GitHub is where people build software."
              />
              <linkedIn-button
                shareUrl="https://github.com/"
                shareDescription="GitHub is where people build software."
              />
            </main>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import ChattyLogo from "@/components/ChattyLogo";
import TwitterButton from "vue-share-buttons/src/components/TwitterButton";
import FacebookButton from "vue-share-buttons/src/components/FacebookButton";
import LinkedInButton from "vue-share-buttons/src/components/LinkedInButton";
export default {
  name: "Login",
  components: {
    ChattyLogo,
    TwitterButton,
    FacebookButton,
    LinkedInButton,
  },
};
</script>
<style scoped>
.btn-login {
  background-color: black;
  border-color: black;
}

.card-login {
}
</style>
