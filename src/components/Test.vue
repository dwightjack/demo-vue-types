<script lang="ts" setup>
import { string } from "vue-types";

defineProps({
  msg: string(),
});
</script>
<template>
  <p>{{ msg }}</p>
</template>
