<script setup>
    const props = defineProps([
        'url'
    ])
</script>

<template>
    <a :href="props.url"
        class="flex sm:inline-flex justify-center items-center  transition ease-in-out border-2 px-4 py-2 rounded border-gray-700 text-slate-400 hover:bg-gray-800">
        <slot></slot>
    </a>
</template>