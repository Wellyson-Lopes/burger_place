<template>
  <div class="message-container">
    <p>{{ msg }}</p>
  </div>
</template>

<script>
export default {
  name: "MessageSucces",
  props: {
    msg: String
  }
}
</script>

<style scoped>
.message-container {
  color: #028f09;
  background-color: #b0ffbf;
  border: 2x solid #caf6d5;
  border-radius: 5px;
  padding: 10px;
  max-width: 400px;
  margin: 30px auto;
}
</style>