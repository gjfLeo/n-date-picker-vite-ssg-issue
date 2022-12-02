<template>
  <div class="item">
    <n-button>Button</n-button>
  </div>
  <div class="item">
    <n-input></n-input>
  </div>
  <div class="item">
    <!-- Comment next line to build successfully -->
    <n-date-picker></n-date-picker>
  </div>
</template>

<script lang="ts" setup>
import { NButton, NInput, NDatePicker } from "naive-ui";
</script>

<style>
body {
  padding-top: 100px;
  display: flex;
  flex-direction: column;
  align-items: center;
}

.item {
  max-width: 200px;
  text-align: center;
}

.item+.item {
  margin-top: 10px;
}
</style>
