<script setup lang="ts">

</script>

<template>
    
    <h1 class="projects-heading" id="work">Projects<span class="projects-heading--accent">.</span></h1>
    <div class="project-wrapper">
        <div class="image-wrapper" id="orbitr">
        </div>
        <div class="project-text-wrapper" >
            <div class="accent-button">
                <p>Java</p>
            </div>
            <h2 class="project-title">This is my project Orbitr</h2>
            <a href="https://github.com/SABoev20/Orbitr"><p class="project-text">Read more</p></a>
        </div>
    </div>
    <div class="project-wrapper project-wrapper--second">
        <div class="image-wrapper" id="chroma">

        </div>
        <div class="project-text-wrapper">
            <div class="accent-button">
                <p>JS</p>
            </div>
            <h2 class="project-title">This is my project Chroma</h2>
            <a href=""><p class="project-text">Currently in development</p></a>
        </div>
    </div>
    <div class="project-wrapper">
        <div class="image-wrapper" id="neos">
        </div>
        <div class="project-text-wrapper" >
            <div class="accent-button">
                <p>C++</p>
            </div>
            <h2 class="project-title">This is my project Neos</h2>
            <a href="https://github.com/ZYPetkova20/Neos/tree/main"><p class="project-text">Read more</p></a>
        </div>
    </div>
    <div class="project-wrapper project-wrapper--second">
        <div class="image-wrapper" id="b11">

        </div>
        <div class="project-text-wrapper">
            <div class="accent-button">
                <p>JS</p>
            </div>
            <h2 class="project-title">This is my project B11</h2>
            <a href="https://github.com/SYSolakov20/b11"><p class="project-text">Read more</p></a>
        </div>
    </div>
    <div class="project-wrapper">
        <div class="image-wrapper" id="arvos">
        </div>
        <div class="project-text-wrapper" >
            <div class="accent-button">
                <p>C++</p>
            </div>
            <h2 class="project-title">This is my project Arvos</h2>
            <a href="https://github.com/codingburgas/Arvos"><p class="project-text">Read more</p></a>
        </div>
    </div>
    <div class="project-wrapper project-wrapper--second">
        <div class="image-wrapper" id="onsens">

        </div>
        <div class="project-text-wrapper">
            <div class="accent-button">
                <p>C++</p>
            </div>
            <h2 class="project-title">This is my project Onsens</h2>
            <a href="https://github.com/SYSolakov20/onsens"><p class="project-text">Read more</p></a>
        </div>
    </div>
</template>

<style scoped>
    @import '../assets/base.css';
    
    .projects-heading{
        margin-top: var(--section-gap);
        text-align: center;
        font-size: 40px;
        font-family: var(--heading-font);
    }
    .projects-heading--accent{
        color: var(--accent-colour);
    }

    .project-wrapper{
        margin-top: var(--section-gap);
        width: 100%;
        display: flex;
        height: 350px;
        align-items: center;
        justify-content: center;
        gap: 200px;
    }
    .image-wrapper{
        background-color: black;
        width: 650px;
        height: 360px; 
    }
    .project-text-wrapper{
        display: flex;
        flex-direction: column;
        justify-content: center;
        gap: 30px;
    }
    .accent-button{
        display: flex;
        justify-content: center;
        align-items: center;
        background-color: var(--accent-colour);
        width: 235.459px;
        height: 42.442px; 
        font-family: var(--heading-font);
        font-size: 18px;
        color: var(--text-colour-light);
    }
    .project-title{
        font-family: var(--heading-font);
        font-size: 40px;
        width: 470px;
    }
    .project-text{
        font-family: var(--heading-font);
        font-size: 20px;
        text-decoration: underline;
    }
    .project-wrapper--second{
        flex-direction: row-reverse
    }

    #neos{
        background-image: url("../assets/img/neosProject.png");
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center; 
    }

    #onsens{
        background-image: url("../assets/img/onsens.png");
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center; 
    }

    #orbitr{
        background-image: url("../assets/img/orbitr.png");
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center; 
    }
    #chroma{
        background-image: url("../assets/img/chroma.png");
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center; 
    }
    #b11{
        background-image: url("../assets/img/b11.png");
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center; 
    }
    #arvos{
        background-image: url("../assets/img/arvos.png");
        background-size: cover;
        background-repeat: no-repeat;
        background-position: center; 
    }
</style>
