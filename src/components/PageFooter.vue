<template>
    <footer>
        <p>Copyright 2021 Calgary's Coffee Shop</p>
    </footer>
</template>

<script>
// Exporting the footer component so that it can be used or imported to the home page
    export default {
        name: "page-footer"
    }
</script>

<style scoped>
/* Styling the HTML tags that are only applied to this component */
    footer {
        display: grid;
        place-items: center;
        min-height: 10vh;
    }
</style>