<template>
<div class="background">
    <div class="container">
        <div class="box box-black">
            <span class="grey">Are you ready</span>
            <h2>Start a new project</h2>
            <input type="text" placeholder="Enter your email address">
        </div>
        <div class="box box-green">
        <span class="white">What are ou waiting for</span>
            <h2>Let's talk about Work</h2>
            <a href="#">START NOW</a>
        </div> 
    </div>
    <div class="container-client">    
            <img src="../assets/images/client-1-2x.png" alt="">
            <img src="../assets/images/client-3-2x.png" alt="">
            <img src="../assets/images/client-4-2x.png" alt="">
            <img src="../assets/images/client-5-2x.png" alt="">
            <img src="../assets/images/client-7-2x.png" alt="">
            <img src="../assets/images/client-9-2x.png" alt="">
    </div> 
</div>
   
</template>

<script>
export default {

}
</script>

<style scoped lang='scss'>
.background{
    background-color:#fafafa ;
    position: relative;
    height: 300px;

    .container-client{
        width: 1000px;
        margin: auto;
        display: flex;
        justify-content: space-between;
        align-items: center;
        position: relative;
        bottom: 270px;
    }

    .container{
        display: flex;
        justify-content: center;
        align-items: center;
        padding-top: 200px;
        position: relative;
        bottom: 330px;
        .box{
            width: 550px;
            height: 240px;
            box-shadow: 0 0 10px grey;
            border-radius: 8px;
            padding: 40px;
            margin: 0 10px;
            text-align: center;

            h2{
                margin-bottom:60px ;
            }
        }
        .box-green{
            background-color: lightgreen;
            a{
                text-decoration: none;
                color: white;
                background-color:  #000;
                padding: 17px 30px;
                border-radius: 30px;
                font-size: 12px;
                margin-right: 10px;
            }
        }
        .box-black{
            background-color: black;
            color: white
        } 
    }
}    
</style>