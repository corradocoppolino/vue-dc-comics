<template>
  
    <section>

       <button>CURRENT SERIES</button> 

    </section>

</template>

<script>
export default {

}
</script>

<style lang="scss" scoped>

section{
    height: 300px;
    background-image: url(../assets/jumbotron.jpg);
    background-size: cover;
    min-width: 1200px;
    position: relative;
    button{
                background-color: #1882F9;
                border: none;
                color: white;
                padding: 10px 20px;
                font-size: 15px;
                margin-top: 25px;
                cursor: pointer;
                position: absolute;
                bottom: -20px;
                left: 120px;
    }
}

</style>