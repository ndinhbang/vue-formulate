<template>
  <div
    v-if="context.help"
    :id="`${context.id}-help`"
    :class="`formulate-input-help formulate-input-help--${context.helpPosition}`"
    v-text="context.help"
  />
</template>

<script>
export default {
  props: {
    context: {
      type: Object,
      required: true
    }
  }
}
</script>
