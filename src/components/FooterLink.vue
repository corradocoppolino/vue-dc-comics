<template>
    
    <footer>

        

        <div class="container">

            <div class="container-link">

                <div class="link">
                    
                    <div class="colonna">
                        <h2>DC COMICS</h2>
                        <ul>
                            <li><a href="#">Characters</a></li>
                            <li><a href="#">Comics</a></li>                                        
                            <li><a href="#">Movies</a></li>
                            <li><a href="#">TV</a></li>
                            <li><a href="#">Games</a></li>                                        
                            <li><a href="#">Videos</a></li>
                            <li><a href="#">News</a></li>                                        
                        </ul>
                        <h2>SHOP</h2>
                        <ul>
                            <li><a href="#">Shop DC</a></li>
                            <li><a href="#">Shop DC Collectibles</a></li>                                                                              
                        </ul>
                    </div>

                    <div class="colonna">
                        <h2>DC</h2>
                        <ul>
                            <li><a href="#">Term Of Use</a></li>
                            <li><a href="#">Privacy policy (New)</a></li>                                        
                            <li><a href="#">Ad Choise</a></li>
                            <li><a href="#">Advertising</a></li>
                            <li><a href="#">Jobs</a></li>                                        
                            <li><a href="#">Subscripting</a></li>
                            <li><a href="#">Talent Workshop</a></li>
                            <li><a href="#">CPSC Certifacates</a></li>
                            <li><a href="#">Ratings</a></li>                                        
                            <li><a href="#">Shop Help</a></li>
                            <li><a href="#">Contact Help</a></li>                                        
                        </ul>
                    </div>

                    <div class="colonna">
                        <h2>SITES</h2>
                        <ul>
                            <li><a href="#">DC</a></li>
                            <li><a href="#">MadMagazine</a></li>                                        
                            <li><a href="#">DC Kids</a></li>
                            <li><a href="#">DC Universe</a></li>
                            <li><a href="#">DC Power Visa</a></li>                                                                              
                        </ul>
                    </div>

                </div>

            </div>

            

        </div> 

        <div class="logo">

        </div>

    </footer>

</template>s

<script>
export default {

}
</script>

<style lang="scss" scoped>

    footer{
        height: 400px;
        background-image: url(../assets/footer-bg.jpg);
        display: flex;
        min-width: 1200px;
        .logo{
                background-image: url(../assets/dc-logo-bg.png);
                height: 400px;
                width: 100%;
                background-repeat: no-repeat;
                background-position-y: -100px;
            }
        .container{
            margin-left: 120px;
            margin-top: 40px;
            width: 1000px;
        }
    }

    .colonna{
        margin-top: 30px;
        width: 33%;
        float: left;
        h2{
            color: white;
            margin: 15px 0;
            font-size: 18px;
        }
        ul{
        list-style: none;
        li{
            a{
                color: #959595;
                text-decoration: none;
                font-size: 12px;
                line-height: 12px;
            }
        }
    }
    }

</style>