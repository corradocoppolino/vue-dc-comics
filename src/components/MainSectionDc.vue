<template>
    <div>
        
        <div class="container">

            <ul>
                <img src="../assets/buy-comics-digital-comics.png" alt="">
                <li><a href="#">digital comics</a></li>
            </ul>
            <ul>
                <img src="../assets/buy-comics-merchandise.png" alt="">
                <li><a href="#">dc merchandise</a></li>
            </ul>
            <ul>
                <img src="../assets/buy-comics-subscriptions.png" alt="">
                <li><a href="#">subscription</a></li>
            </ul>
            <ul>
                <img src="../assets/buy-comics-shop-locator.png" alt="">
                <li><a href="#">comic shop locator</a></li>
            </ul>
            <ul>
                <img src="../assets/buy-dc-power-visa.svg" alt="">
                <li><a href="#">dc power visa</a></li>
            </ul>

        </div>

    </div>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

    div{
        width: 100%;
        height: 150px;
        background-color: #1882F9;
        display: flex;
        align-items: center;
        justify-content: space-around;
        .container{
            width: 80%;
            margin: auto;
            ul{
                list-style: none;
                display: flex;
                align-items: center;
                img{
                    width: 50px;
                    padding-right: 10px;
                }
                li{
                    display: inline-block;
                    a{
                        text-decoration: none;
                        text-transform: uppercase;
                        color: white;
                        font-size: 13px;
                    }
                }
        }
        }
    }

</style>