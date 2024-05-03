<script setup>
import { ref } from "vue";

let counter = ref(5)

function add() {
    counter.value++
}
</script>

<template>
    <div @click="add" class="bg-blue-500 rounded py-1 px-2 max-w-40 text-center text-white hover:cursor-pointer">
        Número de clicks: {{ counter }}
    </div>
</template>