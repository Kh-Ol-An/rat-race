<template>
    <svg :class="color" :width="width" :height="height" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24">
        <path
            d="M13.862 6h-8c-.553 0-1-.448-1-1s.447-1 1-1h8c.553 0 1 .448 1 1s-.447 1-1 1zM11.862 10h-6c-.553 0-1-.448-1-1s.447-1 1-1h6c.553 0 1 .448 1 1s-.447 1-1 1zM10.862 13c0 .55-.45 1-1 1h-4c-.55 0-1-.45-1-1s.45-1 1-1h4c.55 0 1 .45 1 1z"
        />
        <path
            d="M18.862 2v9c0 .55-.45 1-1 1s-1-.45-1-1V2.5c0-.28-.22-.5-.5-.5h-13c-.28 0-.5.22-.5.5v19c0 .28.22.5.5.5h10.5c.55 0 1 .45 1 1s-.45 1-1 1h-11c-1.1 0-2-.9-2-2V2c0-1.1.9-2 2-2h14c1.1 0 2 .9 2 2z"
        />
        <path
            d="M21.862 18c0 .55-.45 1-1 1h-2v2c0 .55-.45 1-1 1s-1-.45-1-1v-2h-2c-.55 0-1-.45-1-1s.45-1 1-1h2v-2c0-.55.45-1 1-1s1 .45 1 1v2h2c.55 0 1 .45 1 1z"
        />
    </svg>
</template>

<script setup>
defineProps({
    width: {
        type: String,
        required: true,
    },
    height: {
        type: String,
        required: true,
    },
    color: {
        type: String,
        default: 'fill-slate-400',
    },
});
</script>
