<script setup lang="ts">
import { useRoute } from 'vue-router';

const route = useRoute();
</script>

<template>
    <div>
        <h1>Single Project Page {{ route.params.id }}</h1>
        <RouterLink to="/">Home</RouterLink>
    </div>
</template>