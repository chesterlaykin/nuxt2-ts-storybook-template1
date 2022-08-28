<template>
  <Task  :task="{ id: '4', state: 'TASK_INBOX', title: 'First task' }"/>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  name: 'IndexPage'
})
</script>
<style lang="scss" scoped>
  .page {
      background: #2cc5d2;
  }
  </style>