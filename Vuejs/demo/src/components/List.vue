<script>
export default {
  data() {
       return {items: [...Array(100).keys()]}
  }
}
</script>

<template>
  <ul v-for="item in items">
    <li>Item {{ item }}</li>
  </ul>
</template>
 