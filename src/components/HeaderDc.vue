<template>
  <header>

      
        <div class="container">

            <div class="logo">
                <img src="../assets/dc-logo.png" alt="">
            </div>
      
            <div class="list">
                <ul>
                    <li v-for="(element,index) in links" :key="index">
                        <a :href="element.ulr"> {{element.text}} </a>
                    </li>
                </ul>
            </div>
        </div>
      

  </header>
</template>

<script>
export default {
    data(){
        return{
            links:[
                {
                    ulr: '#',
                    text: 'characters',
                    active: false
                },
                {
                    ulr: '#',
                    text: 'comics',
                    active: false
                },
                {
                    ulr: '#',
                    text: 'movies',
                    active: false
                },
                {
                    ulr: '#',
                    text: 'tv',
                    active: false
                },
                {
                    ulr: '#',
                    text: 'games',
                    active: false
                },
                {
                    ulr: '#',
                    text: 'collectibles',
                    active: false
                },
                {
                    ulr: '#',
                    text: 'videos',
                    active: false
                },
                {
                    ulr: '#',
                    text: 'fans',
                    active: false
                },
                {
                    ulr: '#',
                    text: 'news',
                    active: false
                },
                {
                    ulr: '#',
                    text: 'shop',
                    active: false
                }
            ]
        }
    }
}
</script>

<style lang="scss" scoped>

    header{
        height: 100px;
        min-width: 1200px;
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
                    margin-left: 15px;
                    a{
                        text-decoration: none;
                        text-transform: uppercase;
                        font-size: 13px;
                        color: #464646;
                    }
                }
            }
        }

    }

    

</style>