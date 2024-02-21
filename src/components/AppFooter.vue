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
                    <button class="buttn btn btn-danger rounded-0" type="submit">Register</button>
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
    box-shadow: inset 20px 50px 50px 5px #172331;
    padding: 30px;
    align-items: center;

}


.searchBar {

    height: 50px;
    color: lightgrey;
}

.leftSideBar {
    border-left: 7px solid #23374b;

}

// .clbar {
//     width: 7px;
//     height: 60px;

// }

.buttn {
    height: 50px;
}
</style>