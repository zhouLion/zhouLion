<script setup>
import { ref } from 'vue';

const props = defineProps({
    count: {
        type: Number,
        default: 4,
    },
    gap: {
        type: Number,
        default: 10,
    },
})

const elRef = ref()

const layout = () => {

}
</script>

<template>
    <div>
        <img/>
    </div>
</template>