<script>
import AppCardCenter from './AppCardCenter.vue';
import AppPlayer from './AppPlayer.vue';
import AppCardSec from './AppCardSec.vue';
import AppCarousel from './AppCarousel.vue';
import AppFooter from './AppFooter.vue';
import AppFooterCard from './AppFooterCard.vue';
export default {
    data() {
        return {
            cards: [
                {
                    image: "bruce-mars-FWVMhUa_wbY-unsplash.jpg",
                    price: "Free",
                    title: "UI Animation using Sketch 3, Principle App, and Flinto",
                    paragraph: " This online photography course will teach you how to take amazing images and even sell...",
                    info: "Course by : University",


                },
                {
                    image: "course-1-2.jpg",
                    price: "Free",
                    title: "The Ultimate Drawinf Course-Beginner to Advanced",
                    paragraph: " This online photography course will teach you how to take amazing images and even sell...",
                    info: "Course by : University",
                },
                {
                    image: "william-thomas-ny6tO4ItOEY-unsplash.jpg",
                    price: "Free",
                    title: "Your Complete Guide to Photography",
                    paragraph: " This online photography course will teach you how to take amazing images and even sell...",
                    info: "Course by : University",
                },

            ],
            newCards: [
                {
                    image: "news-3-2.jpg",
                    admin: " Admin",
                    school: "University",
                    title: "Peer pressure chamges how teens tackle inequality",
                    more: "Read more",
                },
                {
                    image: "news-2-2.jpg",
                    admin: "Admin",
                    school: "Education",
                    title: "Lewishan Live Mixtape celebrates borough's",
                    more: "Read more",
                },
                {
                    image: "news-1-2.jpg",
                    admin: "Admin",
                    school: "Education",
                    title: "Turner Prize winner's work to open Gold on Film Festival",
                    more: "Read more",

                }

            ],
            carousels: [
                {
                    image: "gallery-3-3.jpg"
                },
                {
                    image: "news-3-2.jpg",
                },
                {
                    image: "gallery-1-3.jpg"
                },
                {
                    image: "gallery-2-3.jpg"
                }
            ]
        };
    },
    components: { AppCardCenter, AppPlayer, AppCardSec, AppCarousel, AppFooter, AppFooterCard }
};
</script>
<template>
    <!-- JUMBO -->
    <main class="container-fluid">
        <div class="containerMain">
            <div class="jumbo">
                <img class="img-fluid" src="../assets/img/02_Landing-Page.jpg" alt="">

            </div>
            <div class="pippo">
                <h1>Professional Development For <br> Coaches And Leaders</h1>
                <button class="buttn">Learn More</button>
            </div>
        </div>
        <div class="firstSection">
            <h2>Since 2000,weve been partnering with education leaders to <br> <span class="markP">increase equity and
                    achievement
                </span> for all
                students.</h2>
        </div>

        <!-- fine del JUMBO -->

        <!-- card -->

        <div class="containerCard">
            <div class="row justify-content-center ">
                <div class="col-3">
                    <div class="card"><img class="imgTools" src="../assets/svg/svg-0.svg" alt="">
                        <p class="pHover"><strong>Online Coaching</strong></p>
                        <p class="lorem">Lorem ipsum dolor sit amet consectetur, adipisicing elit. In quasi dolor excepturi
                            commodi eius
                            asperiores autem ad! </p>
                    </div>
                </div>
                <div class="col-3">
                    <div class="card"><img class="imgTools" src="../assets/svg/svg-1.svg" alt="">
                        <p class="pHover"><strong>Consultation</strong></p>
                        <p class="lorem">Lorem ipsum dolor sit amet consectetur, adipisicing elit. In quasi dolor excepturi
                            commodi eius
                            asperiores autem ad! </p>
                    </div>
                </div>
                <div class="col-3">
                    <div class="card"><img class="imgTools" src="../assets/svg/svg-2.svg" alt="">
                        <p class="pHover"><strong>Life Programs</strong></p>
                        <p class="lorem">Lorem ipsum dolor sit amet consectetur, adipisicing elit. In quasi dolor excepturi
                            commodi eius
                            asperiores autem ad! </p>
                    </div>
                </div>
                <div class="row d-flex">
                    <div class=" col-3"><img class="counter" src="../assets/img/counter-shape-1-1-1.png" alt="">
                        <span class="ciao">6500 + students</span>
                    </div>
                    <div class="col-3"><img class="counter" src="../assets/img/counter-shape-2-1-1.png" alt=""><span
                            class="ciao">200 + online courses</span></div>
                    <div class="col-3"><img class="counter" src="../assets/img/counter-shape-3-1-1.png" alt=""><span
                            class="ciao">100% Happy clients</span></div>
                </div>

            </div>

        </div>
        <div class="row text-center p-4">
            <h1><strong>Recent Courses</strong></h1>
            <p>Whetever you're considering a foundation course or an undergraduate degree master's <br> or a PhD, academics
                is a
                place where students thrive</p>

        </div>
        <div class="row">
            <AppCardCenter v-for="card in cards" :item="card">
            </AppCardCenter>
        </div>
        <div class="">
            <AppPlayer></AppPlayer>
        </div>
        <div class="row text-center p-4">
            <AppCardSec v-for="newCard in newCards" :item="newCard">
            </AppCardSec>
        </div>

        <div class="row">
            <AppCarousel v-for="carousel in carousels" :item="carousel">
            </AppCarousel>
        </div>

    </main>
    <footer>
        <div class="container-fluid">
            <AppFooter></AppFooter>
        </div>
    </footer>
</template>
<style lang="scss" >
main {
    background-color: #ffffff;
}

// inizio del JUmbo
.containerMain {
    .jumbo {
        width: 100%;
        margin-top: 20px;
    }

    .pippo {
        bottom: 500px;
        position: relative;
        text-align: center;

        .buttn {
            color: black;
            padding: 10px 30px;
            border: 1px solid black;
            border-radius: 0;
            background-color: inherit;
        }
    }

    .buttn:hover {
        color: white;
        background-color: #d74d52;

    }

}

.firstSection {
    margin-bottom: 200px;
}

h2 {
    text-align: center;

}

.markP {
    color: brown;
}

// fine del jumbo

// inizio delle card

.containerCard {
    background-color: #ffffff;
    // width: 1080px;
    display: flex;
    justify-content: center;
    align-items: center;
    // margin-left: 400px;
}

.row {

    justify-content: center;
}

.col-3 {

    width: 600px;
    height: 300px;
    background-color: #ffffff;
    display: flex;
    justify-content: center;
}

.card {
    width: 600px;
    align-items: center;

}

.imgTools {
    width: 60px;
    margin-top: 30px;
    margin-bottom: 20px;

}

.lorem {
    margin: 20px;
}

.pHover:hover {
    color: #d74d52;
    font-size: 20px;
}

.counter {
    width: 100px;
    height: 80px;
    margin-top: 100px;
    position: absolute;
}

.ciao {
    position: relative;
    margin-top: 130px;
}
</style>