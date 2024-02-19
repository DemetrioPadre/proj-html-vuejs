<script>

export default {};
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
            </div>

        </div>

    </main>
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
    display: flex;
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
</style>