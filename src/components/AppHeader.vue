<script>

export default {
    data() {
        return {
            titleClass: 'title'
        };
    }

};
</script>

<template>
    <div class="container">
        <div class="logo">
            <img src="../assets/img/Logo.jpg" alt="">
        </div>
        <div class="headerLink">
            <!-- aggiungere un hover come in spotify quando si clicca usando il title class creato sopra-->
            <ul>
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
    width: 1080px;
    height: 80px;
    background-color: white;
    display: flex;
    justify-content: space-between;


    img {
        height: 140px;
        position: relative;
        margin-top: 30px;
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

        a:hover {
            color: #d74d52;
            border-bottom: 1px solid #d74d52;
            padding: 5px;

        }
    }
}
</style>