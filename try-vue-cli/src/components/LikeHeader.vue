<template>
  <div>
    <slot name="title"></slot>
    <p>いいねの数</p>
    <slot name="number"></slot>
    <p>{{ headerText }}</p>
  </div>
</template>

<script>
export default {
  props: ['headerText']
}
</script>

<style scoped>
h1 {
  color: red;
}
</style>
