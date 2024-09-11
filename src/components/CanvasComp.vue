<template>
    <div class="canvas-outer">
        <individual-tree-object-comp v-for="( item, i ) in shownObjects" :key="i" :data="item" />
    </div>
</template>

<script setup>
import {ref} from "vue";
import objects from "../assets/objects.json"
import IndividualTreeObjectComp from "@/components/IndividualTreeObjectComp.vue";

const shownObjects = ref(objects)
</script>

<style scoped lang="scss">
.canvas-outer {
    width: 100%;
    background-color: #7a7a7a;
    border-radius: 4px;
    padding: 2rem;
    margin-top: 4rem;
    display: flex;
    flex-wrap: wrap;
    gap: 2rem;
}
</style>
