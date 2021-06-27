<template>
  <div class="left-message-header">
    <div
      class="
        border
        p-2
        d-flex
        justify-content-between
        align-items-center
        bg-light
      "
    >
      <div class="user-icon">
        <img
          src="../../assets/images/avatar.png"
          class="card-img-top avatar mx-auto d-block"
          alt="..."
        />
      </div>
      <div class="setting-icons-right">
        <img
          src="../../assets/images/icons/chat-icon.png"
          width="25px"
          alt=""
        />
        <img
          src="../../assets/images/icons/refresh-icon.png"
          width="25px"
          alt=""
        />
        <img
          src="../../assets/images/icons/menu-icon.png"
          width="25px"
          alt=""
        />
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
</style>
