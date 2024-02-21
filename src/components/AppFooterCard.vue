<script>
export default {
    props: {
        item: Object,
    }

};
</script>
<template>
    <div class="col-3 mt-5 ">
        <div class="card">
            <div class="card-body ">
                <h4>{{ item.title }}</h4>
                <p>{{ item.address }}</p>
                <p>{{ item.phone }}</p>
                <p>{{ item.mail }}</p>
                <p>{{ item.privacy }}</p>
                <p>{{ item.terms }}</p>
                <p>{{ item.coockie }}</p>
                <p>{{ item.map }}</p>
                <p>{{ item.accomodation }}</p>
                <p>{{ item.arts }}</p>
                <p>{{ item.service }}</p>
                <p>{{ item.coonference }}</p>
                <p>{{ item.fb }}</p>
                <p>{{ item.admission }}</p>
                <p>{{ item.contact }}</p>
                <p>{{ item.fq }}</p>
                <p>{{ item.info }}</p>
                <p>{{ item.privacy }}</p>

            </div>
        </div>
    </div>
</template>
<style lang="scss"></style>