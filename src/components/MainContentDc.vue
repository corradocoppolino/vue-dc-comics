<template>
    
    <div>
        
        <main>

            <div class="container">

                <div class="container-photo">

                    <div class="box" v-for="(element,index) in comics" :key="index">
                        <div class="box-img">
                            <img :src="element.thumb" alt="">
                        </div>
                        <h3>{{element.series}}</h3>
                    </div>

                    <button><h4>LOAD MORE</h4></button>

                </div>

            </div>

        </main>

    </div>

</template>

<script>

import comics from '@/assets/data/dc-comics.js'

export default {
    data(){
        return{
            comics
        }
    },
    mounted(){
        console.log(comics);
    }


}
</script>

<style lang="scss" scoped>

    main{
        width: 100%;
        height: 500px;
        background-color: #1C1C1C;
        min-width: 1200px;
    }
    .container{
        width: 80%;
        height: 100px;
        margin: auto;
        .container-photo{
            width: 100%;
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            .box{
                width: calc(100%/6);
                margin-top: 40px;
                .box-img{
                    max-height: 150px;
                    overflow: hidden;
                    img{
                        width: 150px;
                        background-color: bisque;
                    }
                }
                h3{
                    margin-top: 10px;
                    color: white;
                    text-transform: uppercase;
                    font-size: 10px;
                    width: 150px;
                    word-break: break-all;
                }
            }
            button{
                background-color: #1882F9;
                border: none;
                color: white;
                padding: 10px 50px;
                font-size: 10px;
                margin-top: 25px;
                cursor: pointer;
            }
        }
    }

</style>