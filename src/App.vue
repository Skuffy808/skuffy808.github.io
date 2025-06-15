<script setup>
import Hero from './components/Hero.vue';
import Card from './components/Card.vue';
</script>


<template>
  <div class="min-h-screen bg-gradient-to-br from-blue-500 via-black to-pink-500 text-white flex flex-col items-center justify-center gap-8 px-4 py-12">
    <Hero />
    <Card card-title="Skuffy's Tavern" card-description="The personal discord server of the one and only Skuffy" card-image="skuffy.png" card-link="https://discord.gg/U5mH8wJBMk"/>
    <Card card-title="Game.dev()" card-description="Find people to collaborate with and make games!" card-image="game.dev().png" card-link="https://discord.gg/C8qgknw7H3"/>
    <Card card-title="Hangout Heaven" card-description="A discord server for people to come together and hangout." card-image="hangout-heaven.png" card-link="https://discord.gg/MjtcVEMAzK"/>
  </div>
</template>

