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
                <span></span> <span>{{ item.admin }}</span>
                <span></span><span>{{ item.school }}</span>
                <h5>{{ item.title }}</h5>
                <p>{{ item.more }}</p>
            </div>

        </div>
    </div>
</template>
<style lang="scss"></style>