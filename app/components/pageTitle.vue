<template>
    <section>
        <h1 class="font-bold text-5xl p-3">{{ title }}</h1>
    </section>
</template>

<script setup lang="ts">
    defineProps(
        {
            title: {
                type: String,
                required: true
            }
        }
    )
</script>