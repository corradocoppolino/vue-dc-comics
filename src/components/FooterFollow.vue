<template>
  
    <footer>

        <div class="container">

            <button>sign-up now!</button>

            <div class="icons">
                <h4>FOLLOW US</h4>
                <img src="../assets/footer-facebook.png" alt="">
                <img src="../assets/footer-twitter.png" alt="">
                <img src="../assets/footer-youtube.png" alt="">
                <img src="../assets/footer-pinterest.png" alt="">
                <img src="../assets/footer-periscope.png" alt="">
            </div>

        </div>

    </footer>

</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

    footer{
        background-color: #303030;
        height: 100px;
        width: 100%;
        min-width: 1200px;
        .container{
            width: 80%;
            height: 100%;
            margin: auto;
            display: flex;
            align-items: center;
            justify-content: space-between;
        }
    }

    button{
        border: 2px solid #1A87FF;
        padding: 10px;
        text-transform: uppercase;
        background-color: transparent;
        color: white;
        cursor: pointer;
    }

    .icons{
        display: flex;
        align-items: center;
        h4{
            color: #1A87FF;
            margin-right: 20px;
            font-size: 15px;
            cursor: pointer;
        }
        img{
            height: 30px;
            width: 30px;
            margin-right: 15px;
            cursor: pointer;
        }
    }


</style>