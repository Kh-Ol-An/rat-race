<template>
    <svg
        :class="color"
        :width="width"
        :height="height"
        viewBox="0 0 24 24"
        xmlns="http://www.w3.org/2000/svg"
    >
        <path d="m0 19.216 5.414 4.784h15.882l2.274-3.195-23.568-1.589z"/>
        <path d="m13.985 0v19.073l7.309.503z"/>
        <path d="m12.989 3.214-10.56 15.027 10.56.713z"/>
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
