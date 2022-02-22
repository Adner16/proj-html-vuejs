<template>
    <div>
        <div class="container">
            <h2>Latest New and Our <span>Blog</span></h2>
            <div class="container-small">
                <div class="row">
                    <div class='col-4'>
                        <img src="../assets/images/serious-businesswoman-with-documents-talking-on-P9Q6LX6-1024.jpg" class="img-fluid" alt="">
                        <div class="card">
                            <span class="grey">May 24,2018 by Alex</span>
                            <h6>Marketing Ideas</h6>
                        </div>
                    </div>
                    <div class="col-4">
                        <img src="../assets/images/Businessman-at-the-desk-in-his-office-resting--1024x768.jpg" class="img-fluid" alt="">
                        <div class="card">
                            <span class="grey">May 24,2018 by Alex</span>
                            <h6>Rest douringworking Hours</h6>
                        </div>
                    </div>
                    <div class="col-4">
                        <img src="../assets/images/simple-home-office-with-tree-PBXRXYB-large-1024x768.jpg" class="img-fluid" alt="">
                        <div class="card">
                            <span class="grey">May 24,2018 by Alex</span>
                            <h6>Develop your startup idea</h6>
                        </div>
                    </div>
                </div>
            </div>
            <div class="btn">
                <a href="#">VIEW ALL POSTS</a>
            </div>
            <div class="third-container">
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
        </div> 
    </div> 
</template>

<script>
export default {

}
</script>

<style scoped lang='scss'>
    .container{
        height: 900px;
        display: flex;
        flex-direction: column;
        align-items: center;
        width: 1200px;
        padding:100px 0 ;
        h2{
            text-align: center;
            margin-bottom: 45px;
        }
        .col-4{
            border-radius: 25px;
            overflow: hidden;
            position: relative;
            .card{
                width: 300px;
                height: 100px;
                position: relative;
                bottom: 50px;
                left: 44px;
                border: 0;
                padding: 20px 30px;
                box-shadow: 0 0 30px grey;
                display: flex;
                flex-direction: column;
                justify-content: end;
                .grey{
                    font-size: 12px;
                    color: grey;
                }
            }
        }
        .btn a{
            text-decoration: none;
            color: white;
            background-color:  #000;
            padding: 17px 30px;
            border-radius: 30px;
            font-size: 12px;
            margin-right: 10px;
        }
    }
    .third-container{
        display: flex;
        padding-top: 200px;
        .box{
            width: 550px;
            box-shadow: 0 0 10px grey;
            border-radius: 8px;
            padding: 50px;
            text-align: center;
            margin-right: 25px;
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
     
     
</style>