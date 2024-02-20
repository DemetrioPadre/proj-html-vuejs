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
            <img src="../assets/img/video-bg-3.jpg" alt="">
        </div>
        <div class="colPlayer">
            <div class="headerCol">
                <p class=" ">Upcoming Events</p>

            </div>
        </div>
    </div>
</template>
<style lang="scss">
.playerContainer {
    margin-top: 200px;

    justify-content: center;
    text-align: center;
}

img {
    margin-left: 300px;
}

.underlineColor {
    color: #d74d52;
    text-decoration: underline;

}

.colContainer {
    display: flex;
}

.colPlayer {
    width: 600px;
    height: 550px;
    background-color: pink;
}

.headerCol {
    display: flex;
    justify-content: center;
    align-items: center;
    align-content: center;
    text-align: center;
    width: 250px;
    height: 80px;
    background-color: #d74d52;
    margin-left: 150px;

}
</style>