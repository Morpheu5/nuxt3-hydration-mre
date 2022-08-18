<template>
    <div>
        <h1>{{ page_title }}</h1>
        <slot />
    </div>
</template>

<script setup>
    const page_title = useState('page_title');
</script>