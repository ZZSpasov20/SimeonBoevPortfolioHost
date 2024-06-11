<script setup lang="ts">

</script>

<template>
    
    <h1 class="certificates-heading" id="certificates">Certificates<span class="certificates-heading--accent">.</span></h1>
    <div class="certificates-wrapper">
        <div class="certificate-wrapper">
            <div class="number-wrapper">
                <p>1</p>
            </div>
            <p class="certificate-text">Information Technology Specialist Java</p>
            <p class="certificate-text certificate-text-end">2023</p>
        </div>
        <div class="certificate-wrapper">
            <div class="number-wrapper">
                <p>2</p>
            </div>
            <p class="certificate-text">Information Technology Specialist JavaScript</p>
            <p class="certificate-text certificate-text-end">2022</p>
        </div>
        <div class="certificate-wrapper">
            <div class="number-wrapper">
                <p>3</p>
            </div>
            <p class="certificate-text">Information Technology Specialist Databases</p>
            <p class="certificate-text certificate-text-end">2024</p>
        </div>
        <div class="certificate-wrapper">
            <div class="number-wrapper">
                <p>4</p>
            </div>
            <p class="certificate-text">Information Technology Specialist Software Development</p>
            <p class="certificate-text certificate-text-end">2024</p>
        </div>
        <div class="certificate-wrapper">
            <div class="number-wrapper">
                <p>5</p>
            </div>
            <p class="certificate-text">Information Technology Specialist Cloud Computing</p>
            <p class="certificate-text certificate-text-end">2024</p>
        </div>
        <div class="certificate-wrapper">
            <div class="number-wrapper">
                <p>6</p>
            </div>
            <p class="certificate-text">Information Technology Specialist Python</p>
            <p class="certificate-text certificate-text-end">2024</p>
        </div>
        <div class="certificate-wrapper">
            <div class="number-wrapper">
                <p>7</p>
            </div>
            <p class="certificate-text">Information Technology Specialist Networking</p>
            <p class="certificate-text certificate-text-end">2024</p>
        </div>
        <div class="certificate-wrapper">
            <div class="number-wrapper">
                <p>8</p>
            </div>
            <p class="certificate-text">Information Technology Specialist HTML and CSS</p>
            <p class="certificate-text certificate-text-end">2024</p>
        </div>
        <div class="certificate-wrapper">
            <div class="number-wrapper">
                <p>9</p>
            </div>
            <p class="certificate-text">Adobe - Certified Professional in Adobe Photoshop</p>
            <p class="certificate-text certificate-text-end">2022</p>
        </div>
        <div class="certificate-wrapper">
            <div class="number-wrapper">
                <p>10</p>
            </div>
            <p class="certificate-text">Adobe - Certified Professional in Visual Design</p>
            <p class="certificate-text certificate-text-end">2022</p>
        </div>
        <div class="certificate-wrapper">
            <div class="number-wrapper">
                <p>11</p>
            </div>
            <p class="certificate-text">Apple Inc. - App Development with Swift Associate</p>
            <p class="certificate-text certificate-text-end">2022</p>
        </div>

        <div class="certificate-wrapper">
            <div class="number-wrapper">
                <p>12</p>
            </div>
            <p class="certificate-text">IT Essentials - Cisco</p>
            <p class="certificate-text certificate-text-end">2023</p>
        </div>
        <div class="certificate-wrapper">
            <div class="number-wrapper">
                <p>13</p>
            </div>
            <p class="certificate-text">Introduction to Cybersecurity - Cisco</p>
            <p class="certificate-text certificate-text-end">2023</p>
        </div>
        <div class="certificate-wrapper">
            <div class="number-wrapper">
                <p>14</p>
            </div>
            <p class="certificate-text">Microsoft Word (Office 2016)</p>
            <p class="certificate-text certificate-text-end">2021</p>
        </div>
        <div class="certificate-wrapper">
            <div class="number-wrapper">
                <p>15</p>
            </div>
            <p class="certificate-text">Microsoft Excel (Office 2016)</p>
            <p class="certificate-text certificate-text-end">2022</p>
        </div>
      
    </div>

</template>

<style scoped>
    @import '../assets/base.css';
    
    .certificates-heading{
        margin-top: var(--section-gap);
        text-align: center;
        font-size: 40px;
        font-family: var(--heading-font);
    }
    .certificates-heading--accent{
        color: var(--accent-colour);
    }
    .certificates-wrapper{   
        height:450px;
        width: 1010px;
        display: flex;
        flex-direction: column;
        overflow-y: scroll;
        margin: auto;
        gap: 30px;
        margin-top: var(--section-gap);
    }
    .certificate-wrapper{
        flex-shrink: 0;
        width:100%;
        height: 130px;
        border: 2.5px solid #000;
        display: flex;
        align-items: center;
        gap: 50px;
    }
    .number-wrapper{
        display: flex;
        align-items: center;
        justify-content: center;
        width: 50px;
        height: 50px; 
        margin-left: 50px;
        background-color: var(--background-colour-dark);
        font-family: var(--text-font);
        font-weight: var(--font-weight-normal);
        font-size: 24px; 
        color: var(--text-colour-light);
    }
    .certificate-text{
        font-size: 24px; 
        font-family: var(--text-font);
        font-weight: var(--font-weight-bold);
    }
    .certificate-text-end{
        margin-left: auto;
        margin-right: 50px;
    }
</style>
