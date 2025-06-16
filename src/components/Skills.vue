<template>
    <div class="w-1/2 bg-white rounded-xl p-4 flex items-start gap-4">
        <div class="flex flex-wrap gap-3">
            <a href="https://skillicons.dev" v-for="icon in icons" :key="icon">
                <img
                    :src="`https://skillicons.dev/icons?i=${icon}`"
                    class="w-12 h-12 object-contain"
                    :alt="icon"
                />
            </a>
        </div>
    </div>
</template>

<script setup>
const icons = [
  'github', 'git', 'tailwind', 'vue', 'react', 'vite',
  'python', 'html', 'css', 'javascript', 'vscode', 'godot', 'markdown', 'discord'
];
</script>