<template>
    <div>
        <TopBanner>
            <template #bigtitle><slot name="bigtitle" /></template>
            <template #smalltitle><slot name="smalltitle" /></template>
        </TopBanner>
        <slot />
    </div>
</template>
