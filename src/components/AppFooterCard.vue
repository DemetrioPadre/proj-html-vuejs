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
                <p class="hover">{{ item.address }} </p> + <i class="fa-brands fa-youtube"></i>
                <p class="hover">{{ item.phone }}</p>
                <p class="hover">{{ item.mail }}</p>



                <p class="hover">{{ item.privacy }}</p>
                <p class="hover">{{ item.terms }}</p>
                <p class="hover">{{ item.coockie }}</p>
                <p class="hover">{{ item.map }}</p>



                <p class="hover">{{ item.accomodation }}</p>
                <p class="hover">{{ item.arts }}</p>
                <p class="hover">{{ item.service }}</p>
                <p class="hover">{{ item.coonference }}</p>
                <p class="hover">{{ item.fb }}</p>

                <p class="hover">{{ item.admission }}</p>
                <p class="hover">{{ item.contact }}</p>
                <p class="hover">{{ item.fq }}</p>
                <p class="hover">{{ item.info }}</p>
                <p class="hover">{{ item.privacyN }}</p>




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
    padding: 10px;
}
</style>