<template>
    <article id="ownerSection">
        <h2>Meet Our Owner</h2>
        <div id="ownerContainer">
            <img src="https://www.wallisphoto.com/IMAGES/2018/Corporate/Large/Nikisa026.jpg" alt="A headshot of a woman with makeup and dark, brown medium length hair parted to the side, smiling at the camera. She is also wearing a black v-neck blouse.">
            <div id="ownerMessage">
                <h3>Meghan Perkins</h3>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ab ex, asperiores dolor obcaecati impedit dolores consequatur aperiam veritatis, iusto rerum odit qui corporis fugiat deserunt corrupti, et voluptatem suscipit dolorem? Lorem, ipsum dolor sit amet consectetur adipisicing elit. Fugit deserunt ad, quod nostrum illum similique eaque reiciendis, odit commodi, doloribus impedit velit saepe. Ea excepturi quidem fugiat tempora, perspiciatis minus. Lorem ipsum dolor sit amet consectetur adipisicing elit. Tempora neque, hic culpa cupiditate voluptatibus id facilis expedita veniam non alias voluptatum quisquam!</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Recusandae, quisquam numquam unde illo odit nulla tempora suscipit fuga modi magni dolorem? Minus corrupti quod iusto totam asperiores soluta aliquid! Dicta! Lorem ipsum dolor sit amet consectetur adipisicing elit.</p>
            </div>
        </div>
    </article>
</template>

<script>
// Exporting the owner component so that it can be used or imported to the body component
    export default {
        name: "page-body-owner"
    }
</script>

<style scoped>
/* Styling the HTML tags that are only applied to this component */
    #ownerSection {
        display: grid;
        place-items: center;
        row-gap: 15vh;
        padding: 7% 0%;
        text-align: left;
    }

    #ownerContainer {
        display: grid;
        place-items: center;
        grid-template-columns: 1fr 1fr;
        width: 80%;
    }

    #ownerMessage  {
        display: grid;
        place-items: center;
        row-gap: 20px;
    }

    #ownerMessage > h3 {
        justify-self: start;
        font-size: 1.5rem;
    }

    h2 {
        font-size: 2rem;
    }

    img {
        width: 25vw;
    }
</style>