<script setup>
import { ElButton, ElRow, ElTable, ElMessageBox } from "element-plus";
import { ref } from "vue";

const i = ref(0);
</script>

<template>
  <ElButton @click="() => {
    ElMessageBox.alert('an alret')
  }"></ElButton>
  <ElButton @click="() => {
    i++;
  }
    ">{{ i }}</ElButton>
  <ElRow></ElRow>
</template>

<style scoped></style>
