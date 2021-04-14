<template>
    <article id="bestSellersSection">
        <h2>Best Sellers</h2>
        <div id="bestSellersContainer">
            <div class="bestSellersCard">
                <img src="https://images.pexels.com/photos/977876/pexels-photo-977876.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="">
                <h4>Americano</h4>
                <p>$4</p>
            </div>
            <div class="bestSellersCard">
                <img src="https://images.unsplash.com/photo-1503481766315-7a586b20f66d?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1635&q=80" alt="">
                <h4>Latte</h4>
                <p>$4</p>
            </div>
            <div class="bestSellersCard">
                <img src="https://www.nespresso.com/ncp/res/uploads/recipes/nespresso-recipes-CAPPUCCINO-BANANA-SESAME-SEEDS.jpg" alt="">
                <h4>Cappuccino</h4>
                <p>$4</p>
            </div>
        </div>

    </article>
</template>

<script>
    export default {
        name: "page-body-best-sellers"
    }
</script>

<style scoped>
    #bestSellersSection {
        display: grid;
        place-items: center;
        row-gap: 15vh;
        padding: 7% 0%;
        background: #DFD6D1;
    }

    h2 {
        font-size: 2rem;
    }

    #bestSellersContainer {
        display: grid;
        place-items: center;
        grid-template-columns: auto auto auto;
        column-gap: 10vw;
    }

    .bestSellersCard {
        display: grid;
        place-items: center;
        row-gap: 15px;
        background: whitesmoke;
        padding: 5%;
        box-shadow: 1px 1px 5px grey;
    }

    h4 {
        font-size: 1.1rem;
    }

    img {
        width: 20vw;
        height: 15vw;
    }
</style>