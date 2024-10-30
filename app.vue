<template>
  <div class="a">
    <Button variant="secondary" class="relative h-full w-full" size="sm">
      123
    </Button>
    <div>pos: {{ x }}, {{ y }}</div>
  </div>
</template>
<script setup lang="ts">
const { x, y } = useMouse()
_get(x, '123')
</script>
<style lang="scss" scoped>
.a {
  .b {
    position: relative;
    width: 100%;
  }
}
</style>
