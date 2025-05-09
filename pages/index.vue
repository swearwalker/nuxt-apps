<template>
    <main class="main">
        <h1>{{ $t('title') }}</h1>
        <Button @click="showWelcomeAlert">Welcome button</Button>
    </main>
</template>

<script setup lang="ts">
import { Button } from '~/components/ui/button';

const showWelcomeAlert = () => {
    alert('Welcome to the Apps!');
};
</script>