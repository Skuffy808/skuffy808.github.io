<template>
  <a
    :href="cardLink"
    target="_blank"
    rel="noopener noreferrer"
    class="w-1/2 bg-white rounded-xl p-6 flex items-start gap-4
           transition-transform duration-300
           dark:bg-gray-800
           hover:scale-105"
  >
    <img :src="getImageUrl(cardImage)" alt="Card image" class="max-w-15 rounded-xl"/>

    <div>
      <h2 class="text-xl font-bold text-gray-900 dark:text-white">{{ cardTitle }}</h2>
      <p class="text-gray-600 dark:text-gray-300">{{ cardDescription }}</p>
    </div>
  </a>
</template>

<script>
export default {
  props: ['cardTitle', 'cardDescription', 'cardImage', 'cardLink'],
  methods: {
    getImageUrl(filename) {
      return new URL(`../assets/${filename}`, import.meta.url).href;
    }
  }
};
</script>
