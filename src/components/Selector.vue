<script setup lang="ts">
import { ref } from 'vue'
import { NSelect } from 'naive-ui'

const selectedValue = ref(null)
const options = [
    {
        label: "place holder 1",
        value: 0
    },
    {
        label: "to be replaced",
        value: 1
    },
    {
        label: "by activities from",
        value: 2
    }, {
        label: "indexedDB",
        value: 3
    }
]
</script>

<template>
    <h1> 我要去做</h1>
    <n-select v-model:value="selectedValue" filterable placeholder="行动" :options="options" />
</template>
