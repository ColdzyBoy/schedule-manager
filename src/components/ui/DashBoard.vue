<script setup lang="ts">
import InfoBox from "../layout/InfoBox.vue";


</script>

<template>
    <div class="dash-board">
        <section class="dash-board__header">
            <h2 style="font-weight: normal"><span style="font-weight: bold">김원재 대리</span>님, 안녕하세요!</h2>
            <div class="dash-board__date">{{ new Date() }}</div>
        </section>
        <InfoBox :headerTitle="'금일 스케줄'" :contents="[1]"/>
        <InfoBox :headerTitle="'공지 및 설문'" :contents="[2,3]"/>
    </div>
</template>

<style scoped>

</style>