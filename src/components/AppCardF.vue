<script>
export default {
    props: {
        item: Object,
    }

};
</script>
<template>
    <div class="col-3 mt-5  d-flex">
        <div class=" card border-0 ">
            <div class="card-body ">

                <h4>{{ item.title }}</h4>
                <p class="hover"><i class="fa-solid fa-angle-right"></i>{{ item.admission }}</p>
                <p class="hover"><i class="fa-solid fa-angle-right"></i>{{ item.contact }}</p>
                <p class="hover"><i class="fa-solid fa-angle-right"></i>{{ item.fq }}</p>
                <p class="hover"><i class="fa-solid fa-angle-right"></i>{{ item.info }}</p>
                <p class="hover"><i class="fa-solid fa-angle-right"></i>{{ item.privacyN }}</p>

            </div>
        </div>
    </div>
</template>
<style lang="scss" scoped>
.col-3 {
    color: white;
    background-color: #192735;
}

.card {
    color: white;
    background-color: #192735;
}

.card-body {
    color: white;
    background-color: #192735;
}

.hover:hover {
    color: #D74D52;
    padding-left: 10px;
}
</style>