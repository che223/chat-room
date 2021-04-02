<template>
  <div class="chatList">
    <div class="chat-search">
      <el-input
        placeholder=""
        suffix-icon="el-icon-search"
        v-model="searchInfo"
        size="small"
      >
      </el-input>
    </div>
    <div class="my-chats">
      <div class="chat-item">
        <img
          src="https://dss3.bdstatic.com/70cFv8Sh_Q1YnxGkpoWK1HF6hhy/it/u=3112590625,4020018870&fm=26&gp=0.jpg"
          alt=""
        >
        <div class="chat-info">
          <div class="chat-name">孙千</div>
          <div class="latest-word">在吗？大电击文库骄傲考试都快</div>
        </div>
        <div class="chat-time">14:47</div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      searchInfo: '',
    };
  },
};
</script>
