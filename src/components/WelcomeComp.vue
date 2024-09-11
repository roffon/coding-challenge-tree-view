<template>
    <div class="welcome-outer">
        <div class="logo-container">
            <img src="/src/assets/logo.png" />
        </div>
        <div class="d-flex flex-column justify-center ga-3 w-33 totally-not-improvised-welcome-text-container">
            <h1><span>Welcome</span>, dear coder!</h1>
            <h3>
                We, the ROFFON Frontend Development Department wish to welcome you to our Tree View coding
                hiring challenge.
            </h3>
            <p>
                Below this totally <i>not</i> improvised welcome component you'll find all the details
                needed to start the coding challenge. We wish you all the luck and hope to welcome you
                to our team soon, and start making totally <i>not</i> improvised components like this one
                together!
            </p>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped lang="scss">
.welcome-outer {
    width: 100%;
    display: flex;
    justify-content: center;
}

.logo-container {
    max-width: 500px;
    height: 500px;
    img {
        width: 100%;
        height: auto;
    }
}

.totally-not-improvised-welcome-text-container {
    padding-bottom: 3rem;
    max-width: 850px;
    h1 {
        font-size: 2.5rem;
        border-bottom: 2px solid #60b083;
        width: fit-content;
        padding: 0 24px 0 0;
        span {
            color: #60b083;
            font-weight: bolder;
        }
    }
    
    h3 {
        font-size: 1.2rem;
        margin-bottom: 2rem;
    }
}
</style>
