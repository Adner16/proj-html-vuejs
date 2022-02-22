<template>
    <div class="container">
        <div class="row top-section">
            <div class="col-5">
                <h2>Our recent <span>web design</span> and <br>  some exemples of <br> past <span>project</span></h2>
            </div>
            <div class="col-7 d-flex align-items-end">
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Et sit nulla beatae qui neque! Facere libero deleniti quae facilis rem similique consequuntur voluptatum possimus, eaque cupiditate quis, doloremque ratione eveniet.</p>
            </div>
        </div>
        <div class="container">
            <div class="row">
                <div class="col-3">
                    <div>
                        <img src="../assets/images/ina-soulis-227104-unsplash-1024x1024.jpg" class="" alt="">
                    </div>
                </div>
                <div class="col-3">
                    <div>
                        <img src="../assets/images/sunisa-misa-531163-unsplash-1024x1024.jpg" class="img-fluid" alt="">
                    </div>
                </div>
                <div class="col-3">
                    <div>
                        <img src="../assets/images/355H-1024x1024.jpg" class="img-fluid" alt="">
                    </div>
                </div>
                <div class="col-3">
                    <div>
                        <img src="../assets/images/photo-1448932252197-d19750584e56-1024x1024.jpg" class="img-fluid" alt="">
                    </div>
                </div>
                <div class="col-3">
                    <div>
                        <img src="../assets/images/business-competition-PB366D8-1024x1024.jpg" class="img-fluid" alt="">
                    </div>
                </div>
                <div class="col-3">
                    <div>
                        <img src="../assets/images/cozy-sofa-in-living-room-PQR5AB9-1024x1024.jpg" class="img-fluid" alt="">
                    </div>
                </div>
                <div class="col-3">
                    <div>
                        <img src="../assets/images/aa9a4539-PQGJ7HU-1024x1024.jpg" class="img-fluid" alt="">
                    </div>
                </div>
                <div class="col-3">
                    <div>
                        <img src="../assets/images/cody-davis-253928-unsplash-1024x1024.jpg" class="img-fluid" alt="">
                    </div>
                </div>
            </div>
            <div class="d-flex justify-content-center mt-5">
                <div class="btn">
                    <a href="#">READ MORE</a>
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
        width: 1200px;
        margin: auto;
        height: 1200px;
        .top-section{
            margin-bottom: 70px;
        .col-5{
            padding-top: 150px;
            span{
                color: lightgreen;
            }
        } 
        }   
        .col-7{
            color: grey;
            font-size: 12px;
        }
         .col-3{
                padding: 2px
            }
            img{
                height: 100%;
                width: 100%;
                object-fit: cover;
            }
        .btn a{
            text-decoration: none;
            color: white;
            background-color: lightgreen;
            padding: 17px 30px;
            border-radius: 30px;
            font-size: 12px;
            margin-right: 10px;
        }    
    }
</style>