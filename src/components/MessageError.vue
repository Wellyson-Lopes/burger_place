<template>
  <div class="message-container">
    <p>{{ msg }}</p>
  </div>
</template>

<script>
export default {
  name: "MessageError",
  props: {
    msg: String
  }
}
</script>

<style scoped>
.message-container {
  color: rgb(233, 5, 5)5;
  background-color: #e99292;
  border: 2x solid #f3c0c0;
  border-radius: 5px;
  padding: 10px;
  max-width: 400px;
  margin: 30px auto;
}
</style>