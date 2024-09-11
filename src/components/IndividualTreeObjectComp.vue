<template>
    <v-sheet width="220" class="text-center px-3 py-4 rounded-lg" color="#4A4A4A">
        <h3 class="font-weight-bold">{{ data.name }}</h3>
    </v-sheet>
</template>

<script setup>
const props = defineProps({
    data: Object,
})
</script>

<style scoped lang="scss">

</style>