<template>
<div class="container d-flex align-items-center">
    <div class="row">
        <div class="col-4 d-flex flex-column jusify-content-center">
            <h2>We are here to make your <span>website</span><br> look more <span>elegant</span><br> and stylish</h2>
            <div>
                <a href="#">VIEW ALL</a>
            </div>
        </div>
        <div class="col-8">
            <div class="container-fluid">
                <div class="row card-section">
                    <div class="col-5 card">
                        <h5>Speed Optimyzation</h5>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div class="col-5 card">
                        <h5>Speed Optimyzation</h5>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div class="col-5 card">
                        <h5>Speed Optimyzation</h5>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                    <div class="col-5 card">
                        <h5>Speed Optimyzation</h5>
                        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit.</p>
                    </div>
                </div>
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
height: 750px;
width: 1200px;
margin: auto;
    .col-4{
        h2{
            font-size: 40px;
            margin-bottom: 50px;
        }
        a{
            text-decoration: none;
            color: white;
            background-color: lightgreen;
            padding: 17px 30px;
            border-radius: 30px;
            font-size: 12px;
            margin-right: 10px;
        }
    }
    .card{
        margin: 15px 10px;
        border: 0;
        padding: 30px;
        box-shadow: 0px 0px 30px lightgray;
        p{
            font-size: 12px;
            color: grey;
        }
    }
    
}    
</style>