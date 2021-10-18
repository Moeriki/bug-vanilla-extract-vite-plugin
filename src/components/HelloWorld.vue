<script setup lang="ts">
import * as styles from './HelloWorld.css'

defineProps<{ msg: string }>()

</script>

<template>
  <h1 :class="styles.title">{{ msg }}</h1>
</template>
