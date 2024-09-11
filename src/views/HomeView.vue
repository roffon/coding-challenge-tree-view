<template>
    <div class="main-outer">
        <welcome-comp />
        <challenge-info-comp />
    </div>
</template>

<script setup>

import WelcomeComp from "@/components/WelcomeComp.vue";
import ChallengeInfoComp from "@/components/ChallengeInfoComp.vue";
</script>

<style scoped lang="scss">
.main-outer {
    max-width: 1250px;
    margin: 0 auto;
}
</style>
