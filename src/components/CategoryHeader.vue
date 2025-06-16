<template>
    <section class="w-1/2 text-left ">
        <h2 class="text-4xl font-bold">{{ title }}</h2>
        <p class="text-lg text-gray-300">{{ description }}</p>
        <hr class="mt-8 border-t border-grey-100 w-full mx-auto">
    </section>
</template>

<script>
export default {
  props: ['title', 'description'],
};
</script>