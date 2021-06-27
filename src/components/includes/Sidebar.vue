<template>
  <aside>
    <div class="card border-0">
      <img
        src="../../assets/images/avatar.png"
        class="card-img-top avatar mx-auto d-block"
        alt="..."
      />
      <div class="card-body">
        <div class="d-flex justify-content-between">
          <div class="d-flex flex-column">
            <h6 class="card-title">Following</h6>
            <p class="text-center">34</p>
          </div>
          <div class="d-flex flex-column">
            <h6 class="card-title">Followers</h6>
            <p class="text-center">134</p>
          </div>
        </div>
      </div>
      <ul class="list-group list-group-flush bg-light">
        <li class="list-group-item">www.exmple.com</li>
        <li class="list-group-item">https://www.facebook.com</li>
        <li class="list-group-item">https://www.linkedin.com</li>
      </ul>
    </div>
  </aside>
</template>

<script>
export default {};
</script>

<style scoped>
.avatar {
  width: 190px;
  position: absolute;
  top: -130px;
  left: 0;
  right: 0;
  border: 4px solid #fff;
  border-radius: 6.25rem;
}

aside .card-body {
  margin-top: 50px;
}
</style>
