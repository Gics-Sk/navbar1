<script setup>
import { ref } from 'vue';

const text = ref("")
</script>
<template>
    <div class="hero">
        <div class="text">
            <p>Salut je m'appel <span class="name">Giovanni SOKENOU</span><br>Je suis un développeur fullstack</p>
        </div>
        <div class="img-hero">
            <img src="" alt="Image de moi">
        </div>
    </div>
</template>
<style scoped>
.hero {
    display: flex;
    justify-content:space-around;
   background-color: #4b4a4a;
   color: #fff;height: 500px;
   align-items: center;
}

.hero .text p{
    font-size: 2rem;
}
.name{
  color: #C85D1B;
  font-size: 2rem;
  
}
</style>