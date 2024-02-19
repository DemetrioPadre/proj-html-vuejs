<script>

export default {

};
</script>

<template>
    <div class="container">
        <div class="logo">
            <img src="/img/Logo.jpg" alt="">
        </div>
        <div class="headerLink">
            <ul> // aggiungere un hover come in spotify
                <li><a href="#"><strong>Home</strong></a></li>
                <li><a href="#"><strong>About</strong></a></li>
                <li><a href="#"><strong>Academics</strong></a></li>
                <li><a href="#"><strong>Courses</strong></a></li>
                <li><a href="#"><strong>News</strong></a></li>
            </ul>
        </div>
    </div>
</template>

<style lang="scss">
.container {
    height: 80px;
    background-color: white;
    display: flex;

    img {
        height: 200px;
    }

    .headerLink {


        ul {
            list-style-type: none;
            display: flex;

            padding: 20px;

            a {
                text-decoration: none;
                color: black;
                margin: 20px;
                display: flex;
                justify-content: space-around;


            }
        }
    }
}
</style>