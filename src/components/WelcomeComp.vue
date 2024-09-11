<template>
    <div class="welcome-outer">
        <div class="logo-container">
            <img src="/src/assets/logo.png" />
        </div>
        <div class="d-flex flex-column justify-center ga-3 totally-not-improvised-welcome-text-container">
            <h1><span>Welcome</span>, dear coder!</h1>
            <h3>
                We, the <span class="font-weight-bold">ROFFON</span> <span class="color-change">Frontend Development
                Department</span> wish to welcome you to our Tree View coding hiring challenge.
            </h3>
            <p>
                Below this totally <i>not</i> improvised welcome component you'll find all the details
                needed to start the coding challenge. We wish you all the luck and hope to welcome you
                to our team soon, and start making totally <i>not</i> improvised components like this one
                together!
            </p>
            <p class="fine-print-text">
                Yes, the logo is moving, you're not crazy
            </p>
        </div>
    </div>
</template>

<script setup>

</script>

<style scoped lang="scss">
@import "src/assets/animations.scss";

.welcome-outer {
    width: 100%;
    display: flex;
    justify-content: center;
}

.logo-container {
    max-width: 500px;
    height: 450px;
    animation: floatAnimation 5s ease-in-out infinite;
    img {
        width: 100%;
        height: auto;
    }
}

.totally-not-improvised-welcome-text-container {
    padding-bottom: 3rem;
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
        margin-bottom: 1rem;
    }
}

.color-change {
    color: #ab5656;
    font-weight: bold;
    animation: colorAnimation 5s infinite linear;
}
</style>
