<script>
export default {
    props: {
        item: Object,
    },
};
</script>
<template>
    <div class="footerContainer">
        <div class="footerNav d-flex justify-content-center">
            <div class="navShadow d-flex justify-content-center">
                <form class="d-flex" role="search">
                    <input class="form-control me-2" type="search" placeholder="Subscribe to our newsletter"
                        aria-label="Search">
                </form>
                <button class="btn btn-danger" type="submit">Register</button>
            </div>

        </div>

    </div>
</template>
<style lang="scss">
.footerContainer {
    height: 1000px;
    background-color: #192735;
}
</style>