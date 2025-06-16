<script setup>
import Hero from './components/Hero.vue';
import Card from './components/Card.vue';
import CategoryHeader from './components/CategoryHeader.vue';
import About from './components/About.vue';
import Skills from './components/Skills.vue';
</script>


<template>
  <div class="min-h-screen bg-gradient-to-br from-blue-500 via-black to-pink-500 text-white flex flex-col items-center justify-center gap-8 px-4 py-12">
    <Hero />
    <CategoryHeader title="About Me" description="A short paragraph about me."/>
    <About />
    <CategoryHeader title="Skills" description="These are all the skills / software that I use."/>
    <Skills />
    <CategoryHeader title="Projects" description="An assortment of projects that I have worked on."/>
    <Card card-title="Vorous" card-description="A 2D platformer game created in one week for a game jam by me and a team. I was the lead developer and programmer." card-image="vorous.png" card-link="https://skuffy808.itch.io/vorous" />
    <CategoryHeader title="Discord Servers" description="Some cool discord servers that I own."/>
    <Card card-title="Skuffy's Tavern" card-description="The personal discord server of the one and only Skuffy" card-image="skuffy.png" card-link="https://discord.gg/U5mH8wJBMk"/>
    <Card card-title="Game.dev()" card-description="Find people to collaborate with and make games!" card-image="game.dev().png" card-link="https://discord.gg/C8qgknw7H3"/>
    <Card card-title="Hangout Heaven" card-description="A discord server for people to come together and hangout." card-image="hangout-heaven.png" card-link="https://discord.gg/MjtcVEMAzK"/>

  </div>
</template>

