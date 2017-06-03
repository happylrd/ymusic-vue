<template>
  <div class="slider" ref="slider">
    <div class="slider-group">
      <slot>
      </slot>
    </div>
    <div class="dots">
    </div>
  </div>
</template>

<script>

</script>

<style scoped lang="stylus" rel="stylesheet/stylus">
  @import "~common/stylus/variable"

  .slider
    min-height: 1px
    .slider-group
      position: relative
      overflow: hidden
      white-space: nowrap
    .dots
      position: absolute
      right: 0
      left: 0
      bottom: 12px
      text-align: center
      font-size: 0
</style>
