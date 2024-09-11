<template>
    <div class="challenge-info-outer">
        <h1 class="title d-flex align-center justify-center ga-3">
            <v-icon>mdi-information-outline</v-icon>
            Challenge info
        </h1>
        
        <h3 class="mt-8">
            In this challenge you will be tasked to build a <span class="highlited">responsive tree-like</span> structure using
            recursivity and advanced <span class="highlited">Vue 3</span> principles. Completing this assignment will prove your
            Javascript knowledge and your proficiency using web development tools and technologies.
        </h3>
        
        <h2 class="text-left highlited mt-6">Here are all the details:</h2>
        <ul class="text-left">
            <li>
                You will be provided with a standard JSON array of objects dynamically rendered
                using the v-for directive. Each component contains a property called
                <span class="highlited">parent_id</span>, among others. You will need to build a tree from
                parents to children contained in a <i>(hint incoming)</i> recursive component based on the
                object's <span class="highlited">parent_id</span> property.
            </li>
            <li>
                Your tree view component <b>needs</b> to be responsive and work seamlessly if more
                objects are added to the array. <i>(You don't need to create an addition function)</i>
            </li>
            <li>
                Your component should be somewhat efficient and the rendering as fast as possible.
            </li>
            <li>
                You will be provided with the individual vue components needed to display the objects.
            </li>
            <li>
                Your result should look 98% like the design you were provided, containing the lines
                drawn between the objects, and everything.
            </li>
            <li>
                To start working on the challenge go ahead and <v-icon>mdi-silverware-fork</v-icon> fork
                this repository and click the <i>totally not too big</i> button below. You should have
                everything you need inside the project. <i>Tip: Work inside the component named <b>CanvasComp</b></i>
            </li>
        </ul>
        
        <v-btn color="#60b083" height="60" variant="outlined" to="/i-totally-know-how-to-solve-this">
            <div>
                <h3>Bring it on!</h3>
                <p>Totally a normal sized button</p>
            </div>
        </v-btn>
    </div>
</template>

<script setup>

</script>

<style scoped lang="scss">
.challenge-info-outer {
    width: 100%;
    text-align: center;
    border: 2px solid grey;
    border-radius: 4px;
    padding: 2rem;
    h1 {
        .v-icon {
            font-size: 2rem;
            color: white;
        }
    }
    
    ul {
        padding: 12px 12px 12px 100px;
    }
    
    .v-btn {
        width: 100%;
        margin-top: 2rem;
        h3 {
            font-weight: bold;
        }
        
        p {
            font-size: 0.5rem;
            color: #e0e0e0;
        }
    }
}
</style>
