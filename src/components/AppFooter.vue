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
            <div class="navShadow  ">
                <div class="leftSideBar d-flex ">
                    <form class="d-flex " role="search">
                        <input class="searchBar form-control rounded-0" type="search"
                            placeholder="Subscribe to our newsletter" aria-label="Search">
                    </form>
                    <button class="btn btn-danger rounded-0" type="submit">Register</button>
                </div>

                <div class="rightSideBar ">
                    <span><span>Insights is Picwik</span>University's thought leadership publication for sharing <br>
                        knowledge
                        on managment, technology and innovation.</span>
                    <p><strong>Take me there</strong><i class="fa-solid fa-angle-right"></i></p>
                </div>
            </div>

        </div>

    </div>
</template>
<style lang="scss">
.footerContainer {
    height: 800px;
    background-color: #192735;
}

.navShadow {
    display: flex;
    justify-content: space-between;
    margin-top: 100px;
}

.searchBar {
    width: 300px;


}
</style>