<template>
    <article id="baristaSection">
        <h2>Meet Our Baristas</h2>
        <div id="baristaContainer">
            <div class="baristaCard">
                <img src="https://images.pexels.com/photos/4349842/pexels-photo-4349842.jpeg?auto=compress&cs=tinysrgb&dpr=2&h=750&w=1260" alt="A smiling women with dark brown, medium length hair, with black t-shirt wearing a light blue-grey apron holding a white to-go coffee cup in her right hand.">
                <p>Marianne</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta, quisquam impedit suscipit veniam similique in sit eum quod nostrum laudantium quaerat labore molestiae harum minus hic dolor ut tenetur sapiente.</p>
            </div>
            <div class="baristaCard">
                <img src="https://images.unsplash.com/photo-1522556189639-b150ed9c4330?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=934&q=80" alt="A smiling man with a dark cyan, collared shirt that has a white patterned design print on it.">
                <p>Brian</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta, quisquam impedit suscipit veniam similique in sit eum quod nostrum laudantium quaerat labore molestiae harum minus hic dolor ut tenetur sapiente.</p>
            </div>
            <div class="baristaCard">
                <img src="https://images.pexels.com/photos/7488711/pexels-photo-7488711.jpeg?auto=compress&cs=tinysrgb&dpr=3&h=750&w=1260" alt="A happy, smiling woman with blonde hair wearing a grey tank top. On top of her grey tank top, she is wearing a dark green apron and holding up a glass coffee cup with one hand.">
                <p>Kayla</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Soluta, quisquam impedit suscipit veniam similique in sit eum quod nostrum laudantium quaerat labore molestiae harum minus hic dolor ut tenetur sapiente.</p>
            </div>
        </div>
    </article>
</template>

<script>
// Exporting the baristas component so that it can be used or imported to the body component
    export default {
        name: "page-body-baristas"
    }
</script>

<style scoped>
/* Styling the HTML tags that are only applied to this component */
    #baristaSection {
        padding: 7% 0%;
        background: #DFD6D1;
    }

    h2 {
        font-size: 2rem;
    }

    #baristaContainer {
        display: grid;
        place-items: center;
        grid-template-columns: auto auto auto;
        width: 100%;
        padding: 0%;
        margin-top: 7vh;
    }

    .baristaCard {
        display: grid;
        place-items: center;
        row-gap: 20px;
    }

    img {
        width: 20vw;
        clip-path: circle();
    }

    img + p {
        font-weight: bold;
        font-size: 1.5rem;
        text-align: center;
        margin-top: -5vh;
    }

    p + p {
        font-size: 0.9rem;
        padding: 0% 15%;
    }
</style>