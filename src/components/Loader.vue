<template>
    <div :class="{ absolute: absolute }" class="spinner-border text-primary"></div>
</template>

<script>
export default {
    props: {
        size: {
            type: Number,
            default: 2
        },
        absolute: {
            type: Boolean,
            default: false
        },
        fixed: {
            type: Boolean,
            default: false
        },
        zIndex: {
            type: Number,
            default: 0
        }
    }
}
</script>