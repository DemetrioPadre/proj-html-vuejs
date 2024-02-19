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
    height: 100px;
    background-color: white;
    display: flex;
    justify-content: space-between;

    img {
        height: 150px;
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

        li:hover {
            color: red;
            border-bottom: 1px solid red;
        }
    }
}
</style>