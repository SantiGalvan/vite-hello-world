<script>
export default {
    name: 'AppHero',
    data: () => ({
        image: '01.jpg'
    })
};
</script>

<template>
    <header>
        <img :src="`../../${image}`" alt="">
    </header>
</template>


<style></style>