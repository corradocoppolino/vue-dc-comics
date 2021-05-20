<template>
  <header>

      
        <div class="container">

            <div class="logo">
                <img src="../assets/dc-logo.png" alt="">
            </div>
      
            <div class="list">
                <ul>
                    <li>
                        <a href="#">characters</a>
                    </li>
                    <li>
                        <a href="#">comics</a>
                    </li>
                    <li>
                        <a href="#">movies</a>
                    </li>
                    <li>
                        <a href="#">tv</a>
                    </li>
                    <li>
                        <a href="#">games</a>
                    </li>
                    <li>
                        <a href="#">collectibles</a>
                    </li>
                    <li>
                        <a href="#">videos</a>
                    </li>
                    <li>
                        <a href="#">fans</a>
                    </li>
                    <li>
                        <a href="#">news</a>
                    </li>
                    <li>
                        <a href="#">shop</a>
                    </li>
                </ul>
            </div>
        </div>
      

  </header>
</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

    header{
        height: 100px;
    }

    .container{

        display: flex;
        justify-content: space-between;
        align-items: center;
        height: 100%;
        width: 80%;
        margin: auto;

        .logo{
            img{
                height: 60px;
            }
        }

        .list{
            ul{
                list-style: none;
                li{
                    display: inline;
                    margin-left: 20px;
                    a{
                        text-decoration: none;
                        text-transform: uppercase;
                        font-size: 15px;
                        color: #464646;
                    }
                }
            }
        }

    }

    

</style>