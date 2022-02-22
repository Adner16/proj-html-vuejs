<template>
  <div class="background">
        <div class="container d-flex justify-content-center align-items-center">
            <div class="box-container">
                <div class="image d-flex flex-column justify-content-center align-items-center">
                    <div class="filter d-flex flex-column justify-content-center align-items-center">
                        <h2 class='number'>280</h2>
                    <span>project</span>
                    <div class="line d-flex">
                        <div class="couple">
                            <span class="number-small">+3500</span><br>
                        <span>USER'COMMENT</span>
                        </div>
                    <div class="couple">
                            <span class="number-small">100%</span><br>
                            <span>HAPPY CLIENTS</span>
                    </div>
                    </div>
                    
                </div>    
            </div>
            <div class="box">
                <h2>We <span class="green">Love</span> what<br> We do</h2>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Ad consectetur esse reprehenderit animi architecto ducimus similique illum nulla beatae voluptas accusamus impedit, porro ex modi nisi. Animi facilis minima eius?</p>
                <i></i><span class="grey">far far away, behind the word mountains</span>
                <i></i><span class="grey">laregge language ocean</span>
                <i></i><span class="grey">far from the countries Vokalia and Consonantia</span>
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
    .background{
        background-color: #fafafa;
        height: 850px;
        .container{
            width: 1200px;
            height: 850px;
            margin: auto;
            position: relative;
            .box-container{
            width: 1000px;
            height: 600px;
                .image{
                    background-image:url('../assets/images/person-with-long-curly-hair-PZ99QM2-2x.jpg') ;
                    background-size: cover;
                    background-repeat: no-repeat;
                    background-position: center;
                    width: 500px;
                    height: 400px;
                    position: absolute;
                    top: 200px;
                    color: white;
                    .filter{
                        width: 500px;
                        height: 400px;
                        background-color: rgba($color: lightgreen, $alpha: 0.9);
                        .number{
                        font-size: 80px;
                        }
                        .number-small{
                            font-size:40px ;
                        }
                        .couple{
                            margin: 10px 20px;
                        }
                    }
                   
                    
                }
                .box{
                    width: 500px;
                    height: 400px;
                    background-color: white;
                    box-shadow: 0 0 20px lightgrey;
                    padding: 50px;
                    position: absolute;
                    top: 250px;
                    left: 550px;
                    .green{
                        color:lightgreen;
                    }   
                    .grey{
                        color: grey;
                        font-size: 12px;
                    }; 
                
                }
            }
        }
    }
</style>