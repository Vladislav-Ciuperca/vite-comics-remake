<script>

import NavSection from './NavSection.vue'
// questo e l'header
export default {
    components: {
        NavSection,
  },
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
            <NavSection title="QQQQQ"></NavSection>
            <NavSection></NavSection>
            <NavSection></NavSection>
            <NavSection></NavSection>
            <NavSection></NavSection>
        </div>
    </div>
</template>
<!-- ///////////////////////////////////////////// -->


<style scoped>
.cont{
    background: #0282f9;
    height: 156px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.container{
    border: 2px dashed red;
    display: flex;
    justify-content: center;
    align-items: center;
}
</style>
