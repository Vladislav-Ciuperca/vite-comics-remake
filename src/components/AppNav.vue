<script>

// questo e l'header
export default {
    data() {
        return {
            sections: [
                {
                    title: "DIGITALCOMICS",
                    image: "/src/assets/img/buy-comics-digital-comics.png"
                },
                {
                    title: "DC MERCHANDISE",
                    image: "/src/assets/img/buy-comics-merchandise.png"
                },
                {
                    title: "SUBSCRIPTION",
                    image: "/src/assets/img/buy-comics-subscriptions.png"
                },
                {
                    title: "COMIC SHOP LOCATOR",
                    image: "/src/assets/img/buy-comics-shop-locator.png"
                },
                {
                    title: "DC POWER VISA",
                    image: "/src/assets/img/buy-comics-digital-comics.png"
                }
            ]

        }
    },
    methods: {
        // placeholder
    },
    mounted() {
        // placeholder
    }
}

</script>



<!-- ///////////////////////////////////////////// -->
<template>
    <div class="cont">
        <div class="container">
            <div class="carta" v-for="section in sections">
                <img :src="section.image" alt="">
                {{ section.title }}
            </div>
        </div>
    </div>
</template>
<!-- ///////////////////////////////////////////// -->



<style scoped>
.cont {
    background: #0282f9;
    height: 156px;
    display: flex;
    justify-content: center;
    align-items: center;
}

.container {
    border: 2px dashed red;
    display: flex;
    justify-content: center;
    align-items: center;
}

.carta {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 50%;
    border: 2px dashed red
}

img {
    height: 40%;
    width: 30%;
}
</style>
