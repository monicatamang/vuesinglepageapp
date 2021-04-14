<template>
    <body>
        <article>
            <h1>Welcome to Calgary's Coffee Shop</h1>
            <div>
                <p>Amazing coffee is just one small part of who we are. To us, coffee represents an incredible opportunity to positively change people’s lives, through meaningful connection and generous servitude. It’s about leaving things better each day- for our people, our relationships and our environment. And, if we can spark someone’s imagination around what coffee can be along the way, then we’ve done our jobs. The world of coffee impacts a staggering amount of people. We take our role and influence in the industry very seriously, and see it as an incredible opportunity and responsibility to improve the lives of the people that link each of us from seed to cup.</p>
                <img id="heroSectionImage" src="https://media3.s-nbcnews.com/j/newscms/2019_33/2203981/171026-better-coffee-boost-se-329p_67dfb6820f7d3898b5486975903c2e51.fit-1240w.jpg" alt="A latte with a leaf design microfoam on top displayed in white ceramic mug placed on top of a white saucer. The white mug and saucer is placed on a wooden table with a small, wooden spoon and coffee beans in the background.">
            </div>
        </article>
    </body>
</template>

// Exporting the body component so that it can be accessible or imported to the home page
<script>
    export default {
        name: "page-body"
    }
</script>

<style scoped>
    body {
        margin-top: 10vh;
        min-height: 80vh;
    }

    article {
        display: grid;
        place-items: center;
        row-gap: 90px;
        padding: 0% 5%;
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

    #heroSectionImage {
        width: 75%;
        border-radius: 10px;
    }
</style>