<script setup lang="ts">

</script>

<template>

    <footer>
        <h6>SIMEON BOEV</h6>
        <p>Full Stack Developer</p>
    </footer>

</template>

<style scoped>
    @import '../assets/base.css';
    
    footer{
        height: 143px; 
        width: 100%;
        display: flex;
        align-items: center;
        justify-content: space-between;
        margin-top: var(--section-gap);
        background-color: var(--background-colour-dark);
        color: var(--text-colour-light);
    }
    h6{
        font-size: 28px; 
        font-family: var(--heading-font);
        padding-left: 150px;
    }
    p{
        font-size: 28px; 
        font-family: var(--text-font);
        font-weight: 300;
        padding-right: 150px;
    }
</style>
