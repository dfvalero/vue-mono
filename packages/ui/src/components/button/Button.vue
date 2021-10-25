<script lang="ts">
import { defineComponent } from 'vue-demi'

export default defineComponent({
  name: 'Button',
})
</script>
<template>
  <div class="button">
    <slot />
  </div>
</template>

<style lang="scss" scoped>
.button {
  border: 1px solid red
}
</style>
