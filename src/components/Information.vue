<script setup lang="ts">
import Dot from '@/components/Dot.vue';
</script>

<template>
    
    <div class="information">
        <div class="heading-wrapper">
            <div class="mini-heading-wrapper">
                <p>SIMEON</p>
                <Dot/>
                <p>BOEV</p>
            </div>
            <p class="heading">Let me talk about
                myself just a 
                little <span class="heading--accent">bit</span>.
            </p>    
        </div>
        <div class="information-wrapper">
            <p class="information-wrapper__title">
                Passionate Full Stack Developer
            </p>
            <p class="information-wrapper__text">
                Hi, I am Simeon Boev - student at VSCPI Burgas who is interested in programming and software development. Get in touch with me and let's discuss the next big project!
            </p>
            <div class="stats-wrapper">
                <div class="stats">
                    <p class="stats__title">PROGRAMMING</p>
                    <p  class="stats__text">5+ YEARS</p>
                </div>
                <div class="stats">
                    <p class="stats__title">CERTIFICATES</p>
                    <p  class="stats__text">15+</p>
                </div>
                <div class="stats">
                    <p class="stats__title">PROJECTS</p>
                    <p  class="stats__text">9+</p>
                </div>
            </div>
        </div>
    </div>

</template>

<style scoped>
    @import '../assets/base.css';
   
    .information{
        margin-top: calc(var(--section-gap) * 2);
        width:100%;
        height:350px;
        display: flex;
        justify-content: space-evenly;
    }
    .heading-wrapper{
        display: flex;
        flex-direction: column;
    }
    .mini-heading-wrapper{
        width:100%;
        display: flex;
        align-items: center;
        font-size: 32px;
        font-family: var(--heading-font);
        font-weight: var(--font-weight-bold);
        gap: 10px;

    }
    .heading{
        margin-top: 30px;
        width:470px;
        font-size: 48px;
        font-family: var(--heading-font);
        font-weight: var(--font-weight-bold);
    }
    .heading--accent{
        color:var(--accent-colour);
    }
    .information-wrapper{
        display: flex;
        flex-direction: column;
        width:600px;
        gap: 30px;
    }
    .information-wrapper__title{
        font-size: 26px; 
        font-family: var(--heading-font);
        font-weight: var(--font-weight-bold);
    }
    .information-wrapper__text{
        font-size: 20px; 
        font-family: var(--text-font);
        font-weight: var(--font-weight-normal);   
    }
    .stats-wrapper{
        width: 100%;
        display: flex;
        align-items: center;
        gap: 50px;
    }
    .stats__title{
        color: var(--accent-colour);
        font-size: 14px; 
        font-family: var(--text-font);
        font-weight: var(--font-weight-normal);   
    }
    .stats__text{
        font-size: 20px; 
        font-family: var(--heading-font);
        font-weight: var(--font-weight-bold);   
    }
</style>
