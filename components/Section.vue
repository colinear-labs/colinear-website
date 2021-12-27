<template>
    <div class="flex py-32 ml-2">
        <h2 class="whitespace-nowrap text-4xl mr-48 text-gray-800" data-aos="fade-up">{{ title }}</h2>
        <p class="text-2xl text-gray-800 mr-12" data-aos="fade-up">{{ subtitle }}</p>
    </div>
</template>

<script>
    export default {
        name: 'Section',
        props: ['title', 'subtitle']
    }
</script>