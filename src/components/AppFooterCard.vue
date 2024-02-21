<script>
export default {
    props: {
        item: Object,
    }

};
</script>
<template>
    <div class="col-3">
        <div class="card">
            <div class="card-body">
                <p>{{ item.title }}</p>
            </div>
        </div>
    </div>
</template>
<style lang="scss"></style>