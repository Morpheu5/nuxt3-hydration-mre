<template>
    <NuxtLayout name="default">
        <template #bigtitle>Some big title</template>
        <template #smalltitle>Some small title</template>
        <hr />
        <div>Some page content.</div>
    </NuxtLayout>
</template>

<script setup>
definePageMeta({
    layout: false
})
</script>