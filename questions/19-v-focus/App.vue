<script setup lang='ts'>
import { ref, Directive } from "vue"

const state = ref(false)

/**
 * Implement the custom directive
 * Make sure the input element focuses/blurs when the 'state' is toggled
 *
*/

const VFocus: Directive<HTMLInputElement, boolean> = {
  mounted(el, { value }) {
    value ? el.focus() : el.blur()
  },
  updated(el, { value }) {
    value ? el.focus() : el.blur()
  }
}

setInterval(() => {
  state.value = !state.value
}, 2000)

</script>

<template>
  <input v-focus="state" type="text">
</template>
