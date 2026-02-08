<template>
    <main class="card">
            <slot />
    </main>
</template>

<style scoped>
    .card{
    width: min(600px, 100%);
    background: #ff3f;
    padding: 18px;
    border-radius: 16px;
    box-shadow: 0 10px 24px rgba(69, 70, 229, 0.2);
}
</style>