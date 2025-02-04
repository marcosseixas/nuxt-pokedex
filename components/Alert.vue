<script setup>
defineProps({
    message: String
});
</script>

<template>
    <div class="bg-green-500 rounded px-2 py-1 text-white">
        {{ message }}
    </div>
</template>