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
    <div class="col-3 mt-5">
        <div class="card border-0 ">
            <img class="card-img-top" :src="generateURL('../assets/img/' + item.image)" alt="">
            <div class="card-body">
                <div><span class="mx-2"><i class="fa-solid fa-user-tie"></i> </span> <span>{{ item.admin
                }}</span>
                    <span class="mx-3"><i class="fa-regular fa-folder-closed"></i></span><span>{{ item.school }}</span>
                </div>

                <h5 class="mt-3">{{ item.title }}</h5>
                <div class="br-red"></div>
                <p class="mt-5">{{ item.more }} <i class="fa-solid fa-angle-right"></i></p>
            </div>

        </div>
    </div>
</template>
<style lang="scss" scoped>
.col-3 {
    margin-bottom: 50px;
}

.card-body {
    text-align: left;
}

.br-red {
    width: 50px;
    border-bottom: 2px solid red;
    margin-top: 20px;
}
</style>