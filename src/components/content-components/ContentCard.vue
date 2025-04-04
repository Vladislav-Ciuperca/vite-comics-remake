<script>
export default {
    props: {
        thumb: 'Object',
        price: 'string',
    }
}
</script>

<template>

    <div class="card">
        <img class="rounded" :src="thumb" alt="">

        <span class="badge text-bg-danger price ">{{ price }}</span>
    </div>
</template>


<style scoped>
.card {
    position: relative;
    cursor: pointer;
}

.price {
    position: absolute;
    top: 3%;
    right: 5%;
}
</style>