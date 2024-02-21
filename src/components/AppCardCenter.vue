<script>
export default {
    props: {
        item: Object,
    },
    methods: {
        generateURL(path) {
            return new URL(path, import.meta.url).href;
        },
    }
};
</script>
<template>
    <div class="col-3">
        <div class="card border-0 ">
            <img class="card-img-top" :src="generateURL('../assets/img/' + item.image)" alt="">
            <div class="card-body">
                <p>{{ item.price }}</p>
                <h5>{{ item.title }}</h5>
                <p>{{ item.paragraph }}</p>
                <p class="info">{{ item.info }}</p>
            </div>

        </div>
    </div>
</template>
<style lang="scss" scoped>
.info {
    color: #d74d52;
}

.card-body {
    background-color: white;
}
</style>