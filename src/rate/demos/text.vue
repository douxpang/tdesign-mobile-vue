<template>
  <t-rate v-model="value" clearable show-text :texts="texts" variant="outline" :gap="defaultGap" />
</template>

<script lang="ts" setup>
import { ref } from 'vue';

const defaultGap = 8;
const value = ref(3);
const texts = ref(['很差', '差', '一般', '好评', '优秀']);
</script>
