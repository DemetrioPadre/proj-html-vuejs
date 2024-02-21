<script>
import AppFooterCard from './AppFooterCard.vue';
import AppCardSVue from './AppCardS.vue';
import AppCardTh from './AppCardTh.vue';
import AppCardF from './AppCardF.vue';
export default {
    data() {
        return {
            footerCards: [
                {
                    title: "Contact Us",
                    address: " 900 Wood Street, MI NY 48607",
                    phone: "+56345678 000-09",
                    mail: "info@example.com"
                },

            ],
            cardSecs: [
                {
                    title: "Support Us",
                    privacy: "Privacy",
                    terms: "Terms",
                    coockie: "Cookie Policy",
                    map: "Sitemap"
                },
            ],
            cardThs: [
                {
                    title: "Explore",
                    accomodation: "Accomodation",
                    arts: "Arts Academics",
                    service: "Central Services",
                    conference: "Conference and Events",
                    fb: "Food and Drink",
                },
            ],
            cardFs: [
                {
                    title: "Visit",
                    admission: "Admission",
                    contact: "Contacts Us",
                    fq: "FAQs",
                    info: "Request Information",
                    privacyN: "Privacy Notice",
                }
            ],






        };
    },
    components: { AppFooterCard, AppCardSVue, AppCardTh, AppCardF }
};
</script>
<template>
    <div class="footerContainer container-fluid">
        <div class="footerNav d-flex justify-content-center">
            <div class="navShadow  ">

                <div class="leftSideBar d-flex ">
                    <p class="clbar"></p>
                    <form class="d-flex " role="search">

                        <input class="searchBar form-control rounded-0" type="search"
                            placeholder="Subscribe to our newsletter" aria-label="Search">
                    </form>
                    <button class="buttn btn btn-danger rounded-0" type="submit">Register</button>
                </div>

                <div class="rightSideBar ">
                    <span><span class="red">Insights is Picwik </span> University's thought leadership publication for
                        sharing
                        <br>
                        knowledge
                        on managment, technology and innovation.</span>
                    <p><strong>Take me there</strong><i class="fa-solid fa-angle-right"></i></p>
                </div>
            </div>

        </div>

        <div class="row">
            <AppFooterCard v-for="footerCard in footerCards" :item="footerCard">
            </AppFooterCard>
            <AppCardSVue v-for="cardSec in cardSecs" :item="cardSec"></AppCardSVue>
            <AppCardTh v-for="cardTh in cardThs" :item="cardTh"></AppCardTh>
            <AppCardF v-for="cardF in cardFs" :item="cardF"></AppCardF>
        </div>

    </div>
</template>
<style lang="scss" scoped>
.footerContainer {
    height: 800px;
    background-color: #192735;
}


.navShadow {
    display: flex;
    justify-content: space-between;
    margin-top: 100px;
    box-shadow: 0px 0px 50px 5px black;
    padding: 30px;
    align-items: center;

    border-left: 7px solid #23374b;

}


.searchBar {
    height: 50px;
    color: lightgrey;
}

.leftSideBar {
    margin-left: 20px;


}


.buttn {
    height: 50px;
}

.rightSideBar {
    color: white;
    margin-left: 50px;
}

.red {
    color: red;
    border-bottom: 1px solid white;
}

.row {
    color: white;
    background-color: #192735;
}
</style>