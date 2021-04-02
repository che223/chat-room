<template>
  <div class="body">
    <chat-list></chat-list>
    <chat-area></chat-area>
    <member-list></member-list>
  </div>
</template>
<script>
import chatList from '@/components/chatList.vue';
import chatArea from '@/components/chatArea.vue';
import memberList from '@/components/memberList.vue';

export default {
  components: {
    chatList,
    chatArea,
    memberList,
  },
};
</script>
