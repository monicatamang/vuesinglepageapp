<template>
    <article id="bestSellersSection">
        <h2>Best Sellers</h2>
        <div id="bestSellersContainer">
            <div class="bestSellersCard">
                <img src="https://images.pexels.com/photos/977876/pexels-photo-977876.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="A small, glass coffee cup filled with Americano coffee on a white, marble table and coffee beans surrounding the base of the cup.">
                <h4>Americano</h4>
                <p>$4</p>
            </div>
            <div class="bestSellersCard">
                <img src="https://images.unsplash.com/photo-1503481766315-7a586b20f66d?ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&ixlib=rb-1.2.1&auto=format&fit=crop&w=1635&q=80" alt="A latte with a microfoam leaf design on top displayed in white ceramic mug with a silver spoon placed beside it which is placed on top of a white saucer. The mug, saucer and silver spoon are displayed on a wooden table.">
                <h4>Latte</h4>
                <p>$4</p>
            </div>
            <div class="bestSellersCard">
                <img src="https://www.nespresso.com/ncp/res/uploads/recipes/nespresso-recipes-CAPPUCCINO-BANANA-SESAME-SEEDS.jpg" alt="A cappuccino that is half-filled in a small glass cup on top of a wooden saucer. The other half of the cup is filled with foam and small slices of banana and sesame seeds placed on top of the foam. The cup and saucer are displayed on a grey table with other fruits placed in the background.">
                <h4>Cappuccino</h4>
                <p>$4</p>
            </div>
        </div>
    </article>
</template>

<script>
// Exporting the best sellers component so that it can be used or imported to the body component
    export default {
        name: "page-body-best-sellers"
    }
</script>

<style scoped>
/* Styling the HTML tags that are only applied to this component */
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