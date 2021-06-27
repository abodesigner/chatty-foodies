<template>
  <div class="user-info">
    <div class="user-info p-2 border">
      <div class="d-flex justify-content-between">
        <div class="d-flex justify-content-start">
          <div class="user-icon mr-2">
            <img
              src="../../assets/images/avatar.png"
              alt=""
              class="img-fluid"
            />
          </div>
          <div
            class="
              user-name
              d-flex
              flex-column
              justify-content-center
              align-items-start
            "
          >
            <h5 class="name mb-0">Henery</h5>
            <p class="user-status text-muted">Busy</p>
          </div>
        </div>
        <div class="time">13:45</div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.user-icon img {
  width: 50px;
}

.msg_time {
  font-size: 0.75rem;
}

.user-status {
  font-size: 0.75rem;
}
</style>
