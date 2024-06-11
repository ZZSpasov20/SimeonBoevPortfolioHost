<script setup lang="ts">

</script>

<template>
    <div class="nav-wrapper">
        <nav>
            <a href="#"><p>Home</p></a>
            <a href="#about"><p>About</p></a>
            <a href="#work"><p>Work</p></a>
            <a href="#certificates"><p>Certificates</p></a>
            <a href="../assets/Simeon Boev CV.pdf" download><p>CV</p></a>
        </nav>
    </div>

</template>

<style scoped>
    @import '../assets/base.css';
    .nav-wrapper{
        display: flex;
        width:100%;
        height: 130px;
    }
    nav{
        padding-left: 250px;
        display: flex;
        align-items: center;
        gap:60px;
        height: 100%;
        font-family: var(--text-font);
        font-size: 22px;
        font-weight: var(--font-weight-normal);
    }
</style>
