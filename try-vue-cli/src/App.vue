<template>
  <div>
    <LikeHeader></LikeHeader>
    <p>いいね({{ number }})</p>
    <LikeNumber :total-number="number" test-props="test"></LikeNumber>
    <LikeNumber :total-number="number" test-props="test"></LikeNumber>
  </div>
</template>

<script>
import LikeHeader from './components/LikeHeader.vue'

export default {
  data() {
    return {
      number: 14
    }
  },
  components: {
    LikeHeader
  }
}
</script>

<style scoped>
div {
  border: 1px solid blue;
}
</style>
