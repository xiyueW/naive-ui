<markdown>
# 基础用法
</markdown>

<script lang="ts">
import { defineComponent } from 'vue'

export default defineComponent({
  data() {
    return {
      value: null
    }
  }
})
</script>

<template>
  <n-radio v-model:value-value="value" value="Definitely Maybe">
    <n-input />
  </n-radio>
</template>
