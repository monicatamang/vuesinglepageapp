<template>
    <body>
        <section>
            <h1>Welcome to Calgary's Coffee Shop</h1>
            <div>
                <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Natus, a. Voluptas quia aperiam error, culpa ipsa eos doloremque praesentium obcaecati saepe perspiciatis. Error nisi, quasi quo facilis voluptatibus minima doloremque. Lorem ipsum dolor, sit amet consectetur adipisicing elit. Nostrum ullam laborum eius tenetur id? Laboriosam possimus sunt, minima ipsum, neque vero, sit alias repudiandae nemo eaque rem eligendi quaerat ea? Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam expedita sapiente veritatis quidem recusandae magnam ipsum ducimus consectetur doloremque sint quam quod, ab incidunt. Suscipit omnis doloremque saepe modi magni?</p>
                <img src="https://media3.s-nbcnews.com/j/newscms/2019_33/2203981/171026-better-coffee-boost-se-329p_67dfb6820f7d3898b5486975903c2e51.fit-1240w.jpg" alt="A latte with a microfoam leaf design on top displayed in white ceramic mug placed on top of a white saucer. The white mug and saucer is placed on a wooden table with a small, wooden spoon and coffee beans in the background.">
            </div>
        </section>
        <!-- Inserting the best sellers, owner and barista components into the HTML file so that it can be used to style the tags and show up on the page -->
        <page-body-best-sellers></page-body-best-sellers>
        <page-body-owner></page-body-owner>
        <page-body-baristas></page-body-baristas>
    </body>
</template>

<script>
// Importing the best sellers, owner and baristas component
import PageBodyBestSellers from "./PageBodyBestSellers";
import PageBodyOwner from "./PageBodyOwner";
import PageBodyBaristas from "./PageBodyBaristas";

// Registering the best sellers, owner and baristas component
// Exporting the body component so that it can be used or imported to the home page
export default {
    name: "page-body",
    components: {
        PageBodyBestSellers,
        PageBodyOwner,
        PageBodyBaristas
    }
}
</script>

<style scoped>
/* Styling the HTML tags that are only applied to this component */
    body {
        margin-top: 10vh;
    }

    section {
        display: grid;
        place-items: center;
        row-gap: 20vh;
        padding: 5% 5% 13% 5%;
    }

    div {
        display: grid;
        place-items: center;
        grid-template-columns: 1fr 1fr;
        column-gap: 50px;
    }

    h1 {
        font-size: 2.5rem;
    }

    p {
        text-align: left;
        line-height: 30px;
    }

    img {
        width: 75%;
        border-radius: 10px;
    }
</style>