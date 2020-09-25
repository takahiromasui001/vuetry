<template>
  <div>
    <slot :fafafa="user" text="text"></slot>
    <hr />
    <slot></slot>
    <p>いいねの数</p>
    <slot></slot>
  </div>
</template>

<script>
export default {
  data() {
    return {
      user: {
        firstName: 'Jack',
        lastName: 'Donald'
      }
    }
  }
}
</script>

<style scoped>
h1 {
  color: red;
}
</style>
