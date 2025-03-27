<script>
// questo e l'header
export default {
    data() {
        return {
            // placeholder
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
                <img src="../assets/img/dc-logo.png" alt="">
            </div>
            <div class="right">
                <a href="#">CHARACTERS</a>
                <a href="#">COMICS</a>
                <a href="#">MOVIES</a>
                <a href="#">TV</a>
                <a href="#">GAMES</a>
                <a href="#">COLLECTABLES</a>
                <a href="#">VIDEOS</a>
                <a href="#">FANS</a>
                <a href="#">NEWS</a>
                <a href="#">SHOP</a>
            </div>
        </div>
    </div>
</template>
<!-- ///////////////////////////////////////////// -->


<style scoped>
.cont {
    background: white;
    color: #242424;
    /* padding: 1rem; */
}

.container{
    width: 1280px;
    margin: auto;
    display: flex;
    justify-content: space-between;
    height:112px ;
}

.right{
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 3rem;
    /* border: 2px dashed red; */
}

.right * {
    font-size: 12.3px;
    color: #696969;
    text-decoration: none;
    font-weight: 800;
    /* border: 2px dashed green; */
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}


.left{
    display: flex;
    justify-content:center ;
    align-items:center ;
}
img{
    width: 80%;
}

</style>
