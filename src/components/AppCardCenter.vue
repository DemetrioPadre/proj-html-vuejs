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
        <div class="card"><img class="" :src="generateURL('../assets/img/' + item.image)" alt="">
            <p class="pHover">{{ item.price }}</p>
            <p class="lorem">{{ item.paragraph }}</p>
        </div>
    </div>
</template>
<style lang="scss"></style>