<template>
    <button class="button">
        <slot />
    </button>
</template>

<script setup>

</script>

<style scoped>
    .button {
        border: none;
        border-radius: 100px;
        background: var(--color-button);
        width: 335px;
        height: 68px;
        padding: 16px 10px;
        font-family: var(--font);
        font-size: 24px;
        font-weight: 400;
        line-height: 36px;
        color: var(--color-font);
        cursor: pointer;
    }
</style>
