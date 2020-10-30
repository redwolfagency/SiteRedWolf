<template>
    <section class="section-home">
        <div class="home-title m">
            <h1 class="-darkRed">RedWolf</h1>
            <h3 class="-darkRed">Digital Agency</h3>
            <ComingSoon class="-darkRed"></ComingSoon>
        </div>
        <div class="home-bg">
            <div class="home-title m -white" >
                <h1 class="-white">RedWolf</h1>
                <h3 class="-white">Digital Agency</h3>
                <ComingSoon></ComingSoon>
            </div>
        </div>
    </section>
</template>

<script>

    import ComingSoon from "@/components/ComingSoon/ComingSoon";
    export default {
        name: "Home",
        components: {
            ComingSoon
        },


    }
</script>

<style scoped>

</style>