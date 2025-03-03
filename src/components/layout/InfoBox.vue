<script setup lang="ts">
import InfoBoxHeader from "./InfoBoxHeader.vue";

const { headerTitle, contents } = defineProps(['headerTitle','contents'])
</script>

<template>
    <!--  하단 클래스 이름 변경 필요 2025.03.03  -->
<div class="dash-board__schedule">
    <div class="dash-board__schedule">
        <InfoBoxHeader :titleText="headerTitle"/>
        <div v-for="(content, index) in contents" :key="index">
            {{ content }}
        </div>
    </div>
</div>
</template>

<style scoped>

</style>