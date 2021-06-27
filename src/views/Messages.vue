<template>
  <div class="messages">
    <MainNavigation />
    <div class="container">
      <div class="message-body my-5">
        <div class="row">
          <div class="col-lg-4 bg-light px-0">
            <LeftMessageHeader />
            <SearchField />
            <UserInfo />
            <UserInfo />
            <UserInfo />
            <UserInfo />
            <UserInfo />
          </div>
          <div class="col-lg-8 px-0">
            <RightMessageHeader />
            <MessageBody />
            <MessageBody />
            <MessageBody />
            <SendMessage />
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import MainNavigation from "@/components/includes/main-navigation";
import LeftMessageHeader from "@/components/ChatMessages/LeftMessageHeader";
import RightMessageHeader from "@/components/ChatMessages/RightMessageHeader";
import SearchField from "@/components/ChatMessages/SearchField";
import UserInfo from "@/components/ChatMessages/UserInfo";
import MessageBody from "@/components/ChatMessages/MessageBody";
import SendMessage from "@/components/ChatMessages/SendMessage";

export default {
  name: "Messages",
  components: {
    MainNavigation,
    LeftMessageHeader,
    RightMessageHeader,
    SearchField,
    UserInfo,
    MessageBody,
    SendMessage,
  },
};
</script>

<style scoped>
.user-icon img {
  width: 50px;
}

.msg_time {
  font-size: 0.75rem;
}
</style>
