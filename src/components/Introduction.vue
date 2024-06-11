<script setup lang="ts">
import Dot from '@/components/Dot.vue';
import GithubButton from '@/components/GithubButton.vue';
import LinkedInButton from '@/components/LinkedInButton.vue';
</script>

<template>
    
    <div class="introduction">
        <h1 class="introduction__heading">HI, I’M <span class="introduction__heading--accent">SIMEON BOEV</span> A FULL-STACK <span class="introduction__heading--accent">DEVELOPER</span></h1>
        <div class="programing-roles">
            <h3>JAVA DEV</h3>
            <Dot/>
            <h3>WEB DEV</h3>
            <Dot/>
            <h3>SQL DEV</h3>
        </div>
        <div class="buttons-wrapper">
            <GithubButton/>
            <LinkedInButton/>
        </div>
    </div>

</template>

<style scoped>
    @import '../assets/base.css';
    
    .introduction{
        width:100%;
        height:550px;
        display: flex;
        justify-content: space-around;
        padding-left: 250px;
        flex-direction: column;
    }
    .introduction__heading{
        width:660px;
        font-size: 57px; 
        font-family: var(--heading-font);
    }
    .introduction__heading--accent{
        color:var(--accent-colour);
    }
    .programing-roles{
        display: flex;
        align-items: center;
        gap:20px;
        font-size: 18px; 
        font-family: var(--heading-font);
    }
    .buttons-wrapper{
        display: flex;
    }
</style>
