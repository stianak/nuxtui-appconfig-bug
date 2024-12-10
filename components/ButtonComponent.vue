<script setup lang="ts">
// import type { ButtonProps } from "@nuxt/ui";
// import type { ButtonProps } from "@nuxt/ui/runtime/components/Button.vue";
import type { ButtonProps } from "#ui/types";
import { defineProps } from "vue";

const props = defineProps<ButtonProps>();
</script>

<template>
  <UButton v-bind="props">Test</UButton>
</template>
