<template lang='jade'>
  .div(class="button")
    {{ text }}
</template>

<script>
export default {
  props: ['text']
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style>
.button {
  padding: 20px 40px;
  background-color: blue;
  color: green;
  border: 5px solid;
}
</style>
