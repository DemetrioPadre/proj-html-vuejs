<script>

export default {};
</script>
<template>
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
    </main>
</template>
<style lang="scss" >
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

        }


    }

    .buttn:hover {
        color: white;
        background-color: red;
    }

}
</style>