<template>
    <header>
        <h1>Calgary's Coffee Shop</h1>
        <a href="#">Home</a>
    </header>
</template>

// Exporting the header component so that it can be accessible or imported to the home page
<script>
    export default {
        name: "page-header"
    }
</script>

<style scoped>
    header {
        display: grid;
        place-items: center;
        grid-auto-flow: column;
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