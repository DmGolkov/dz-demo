<!-- выполнил -->
<template>
    <div> Сегодня: {{ nowDate }}</div>
</template>

<script setup>
    let countryRegion = 'ru-RU';
    const options = {
        weekday: "long",
        year: "numeric",
        month: "long",
        day: "numeric",
    };
    const nowDate = new Date().toLocaleDateString(countryRegion, options);
</script>

<style scoped>
</style>