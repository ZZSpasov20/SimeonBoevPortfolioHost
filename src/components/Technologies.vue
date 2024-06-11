<script setup lang="ts">
import Dot from '@/components/Dot.vue';
</script>

<template>
    
    <div class="technologies-wrapper" id="about">
       <p>Java</p>
       <Dot/>
       <p>Spring Boot</p>
       <Dot/>
       <p>Vue.js</p>
       <Dot/>
       <p>Typescript</p>
       <Dot/>
       <p>MSSQL</p>
    </div>

</template>

<style scoped>
    @import '../assets/base.css';
    
    .technologies-wrapper{
        margin-top: var(--section-gap);
        display: flex;
        justify-content: center;
        align-items: center;
        width:110%;
        height: 90px;
        margin-left: -20px;
        transform: rotate(-4deg);
        background-color: var(--background-colour-dark);
        font-family: var(--text-font) ;
        font-size: 25px; 
        font-weight: var( --font-weight-bold);
        color: var(--text-colour-light);
        gap:100px;
    }

</style>
