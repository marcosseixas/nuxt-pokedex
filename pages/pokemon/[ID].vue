<template>
    <div>
        Pokemon ID: {{ params.ID }}
    </div>
</template>

<script setup lang="ts">
    const{params} = toRefs(useRoute());
</script>