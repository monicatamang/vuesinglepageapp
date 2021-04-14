<template>
    <header>
        <h1>Calgary's Coffee Shop</h1>
        <a href="#home">Home</a>
        <a href="#bestSellersSection">Best Sellers</a>
        <a href="#ownerSection">Owner</a>
        <a href="#baristaSection">Baristas</a>
    </header>
</template>

<script>
// Exporting the header component so that it can be used or imported to the home page
    export default {
        name: "page-header"
    }
</script>

<style scoped>
/* Styling the HTML tags that are only applied to this component */
    header {
        display: grid;
        place-items: center;
        grid-template-columns: 2fr 1fr 1fr 1fr 1fr;
    }

    h1 {
        font-size: 1.5rem;
        color: #83746E;
    }

    a {
        text-decoration: none;
        color: #1F232C;
        font-weight: bold;
    }
</style>