<template>
  <DatePicker
    v-model:value="date"
    date-separator=""
    :labels="{
      year: '年',
      month: '月',
      date: '日'
    }"
    style="max-width: 300px;"
  ></DatePicker>
</template>

<script setup lang="ts">
import { ref } from 'vue'

const date = ref('')
</script>
