<script>
export default {};
</script>
<template>
    <div class="playerContainer">
        <p>"Academics was committed to my success from the moment I attended an Open <br> House. With the support of caring
        <p class="underlineColor">
            advisors, professors, and staff</p> i was able to thrive in courses, gain recognition through
        scholarships,
        and finish <strong>with confidence in my</strong>
        <p class="underlineColor">@academics</p> <strong>abilities</strong>
        </p>

    </div>
    <div class="colContainer">
        <div class="col-6">
            <div class="playerRelative"><i class="fa-solid fa-circle-play" style="color: #fd1800;"></i></div>
            <img class="imgPlayer" src="../assets/img/video-bg-3.jpg" alt="">
        </div>
        <div class="colPlayer">
            <div class="headerCol">
                <p class="  fs-3"><strong>Upcoming Events</strong></p>


            </div>
            <div class="mx-4 mt-5 mb-3">
                <p><strong>Priceton offers admission information sessions <br> anda student-led tours to campus
                        visitors</strong></p>
                <span>Learn more </span>
                <i class="fa-solid fa-angle-right"></i>
                <p class="mt-4"><strong>Admission information sessions and student-led <br> tours to campus
                        visitors</strong>
                </p>
                <span>Learn more </span>
                <i class="fa-solid fa-angle-right"></i>
                <div class="map ">
                    <p><i class="fa-regular fa-map"></i> <strong>Event location</strong><i
                            class="fa-solid fa-angle-right"></i>
                    </p>
                </div>


            </div>
        </div>
    </div>
    <div class="infoBlog mt-5">
        <h2><strong>Latest From Our Blogs</strong></h2>
        <p class="text-center p-2">Whetever you're considering a foundation course or an undergraduate degree master's <br>
            or a PhD, academics is a place where students thrive</p>
    </div>
</template>
<style lang="scss">
.playerContainer {
    margin-top: 200px;

    justify-content: center;
    text-align: center;
}

.underlineColor {
    color: #d74d52;
    text-decoration: underline;

}

.playerRelative {
    font-size: 100px;
    position: relative;
    display: flex;
    justify-content: right;
    margin-right: 100px;
    top: 300px;
}

.imgPlayer {
    margin-left: 300px;


}


.colContainer {
    display: flex;
}

.colPlayer {
    width: 600px;
    height: 550px;
    background-color: #FFFFFF7A;
    margin-top: 200px;

}

.headerCol {
    display: flex;
    justify-content: center;
    align-items: center;
    align-content: center;
    text-align: center;
    width: 300px;
    height: 100px;
    background-color: #d74d52;
    margin-left: 150px;
}

.map {
    display: flex;
    justify-content: center;
    margin-top: 70px;
}
</style>