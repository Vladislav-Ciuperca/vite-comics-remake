<script>
// questo e l'header
export default {
    data() {
        return {
          //placehoplder
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
            <div class="left">

                <div class="sec">
                    <div class="title">
                        DC COMICS
                    </div>
                    <div class="content">
                        <li>Characters</li>
                        <li>Comics</li>
                        <li>Movies</li>
                        <li>TV</li>
                        <li>Games</li>
                        <li>Videos</li>
                        <li>News</li>
                    </div>

                    <div class="title">
                        SHOP
                    </div>
                    <div class="content">
                        <li>Shop DC</li>
                        <li>Shop DC collectibles</li>
                    </div>
                </div>

                <div class="sec">
                    <div class="title">
                        DC
                    </div>
                    <div class="content">
                        <li>Terms Of Use</li>
                        <li>Privacy Policy(New)</li>
                        <li>Ad Choices</li>
                        <li>Advertising</li>
                        <li>Jobs</li>
                        <li>Subscriptions</li>
                        <li>talent Workshop</li>
                        <li>CPSC Certificates</li>
                        <li>Ratings</li>
                        <li>Shop Help</li>
                        <li>Contact Us</li>
                    </div>
                </div>

                <div class="sec">
                    <div class="title">
                        SITES
                    </div>
                    <div class="content">
                        <li>DC</li>
                        <li>MAD magazines</li>
                        <li>DC Kids</li>
                        <li>DC Universe</li>
                        <li>DC Power visa</li>
                    </div>
                </div>

               

                
            </div>
            <div class="right">
                <!-- placeholder -->
            </div>
        </div>
    </div>
</template>
<!-- ///////////////////////////////////////////// -->


<style scoped>

.title{
    font-size: 1.3rem;
    font-weight: 500;
    margin-top: 2rem;
}

.content{
    color: #969696;
    font-size: 15px;
}
li{
    list-style-type: none;
}
.cont {
    background-repeat: no-repeat;
    background-size: cover;
    background-image: url(/src/assets/img/footer-bg.jpg);
}

.right {
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
    background-image: url(/src/assets/img/dc-logo-bg.png);
}

.container {
    display: flex;
}

.container>* {
    width: 50%;
}

.left {
    min-height: 25rem;
    padding: 1px;
    display: flex;
}

.sec{
    /* border: 2px dashed green; */
    padding-right: 4rem;
}

.debug{
    color: red;
}
</style>
