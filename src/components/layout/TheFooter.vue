<template>
    <footer class="container">
        <p>
            {{ ano }}
        </p>
    </footer>
</template>

<script setup lang="ts">
const ano = new Date().getFullYear();
</script>

<style scoped>
footer {
    background: #fff;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    padding: 2rem;
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
}
</style>