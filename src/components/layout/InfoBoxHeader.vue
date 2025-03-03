<script setup lang="ts">
const { titleText } = defineProps(['titleText'])
</script>

<template>
<div class="dash-board__schedule__header">
    <h3>{{ titleText }}</h3>
    <div class="dash-board__schedule__arrow">
        <svg></svg>
    </div>
</div>
</template>

<style scoped>

</style>