<script>

// import NavSection from './NavSection.vue'
// questo e l'header
export default {

    data() {
        return {
            comics: [
                {
                    "title": "DIGITAL COMICS",
                    "img": "/src/assets/img/buy-comics-digital-comics.png"
                },
                {
                    "title": "DC MERCHANDISE",
                    "img": "/src/assets/img/buy-comics-merchandise.png"
                },
                {
                    "title": "SUBSCRIPTION",
                    "img": "/src/assets/img/buy-comics-shop-locator.png"
                },
                {
                    "title": "COMIC SHOP LOCATOR",
                    "img": "/src/assets/img/buy-comics-subscriptions.png"
                },
                {
                    "title": "DC POWER VISA",
                    "img": "/src/assets/img/buy-dc-power-visa.svg"
                },
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
            <!-- <NavSection icon="../assets/img/buy-dc-power-visa.svg" title="DIGITAL COMICS"></NavSection> -->
            <section>

                <span v-for="element in this.comics">
                    <img :src="element.img" alt="">
                    <div class="title">{{ element.title }}</div>
                </span>
            </section>
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
    /* border: 2px dashed red; */
    display: flex;
    justify-content: space-between;
    align-items: center;
    width: 1100px;
}

span {
    display: flex;
    align-items: center;
    /* border: 2px dashed green; */
    width: 100%;
    gap: 1rem;
}

section{
    height: 70px;
    display: flex;
  
}
img {
    width: 20%;
}

.container span:nth-child(3) img {
    width: 15%;
}

span:last-child img {
    width: 25%;
}

span:first-child img {
    width: 20%;
}
</style>
