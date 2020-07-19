<template>
  <span>{{state}}</span>
  <button @click="sum">qweqeqw</button>
</template>

<script lang="ts">
import { ref } from "vue"
export default {
  setup() {
    const state:string = ref('1321')
    function sum() {
      this.state++
    }
    return {state, sum}
  }
}
</script>
