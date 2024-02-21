<script>
export default {
    props: {
        item: Object,
    },
    methods: {
        generateURL(path) {
            return new URL(path, import.meta.url).href;

        }
    },
};
</script>
<template>
    <div class="col-3 mt-5">
        <div class="card d-flex border-0">
            <img class="card-img-top " :src="generateURL('../assets/img/' + item.image)" alt="">
            <!-- <p class="visible"> Driving Innovation</p> -->
        </div>
    </div>
</template>
<style lang="scss" scoped>
.card-img-top:hover {
    opacity: 0.5;
    cursor: pointer;




}
</style>

