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
        <div class="card d-flex">
            <img class="card-img-top" :src="generateURL('../assets/img/' + item.image)" alt="">
        </div>
    </div>
</template>
<style lang="scss"></style>