<template>
    <div class="box">
        <div class="container">
            <div class="info">
                <span id='subtitle'>17 years of experience</span>
                <h2>Focus on Your <br><span>Business</span></h2>
                <p class="grey">Lorem ipsum dolor sit amet consectetur adipisicing elit. Illum sint vitae magnam consectetur voluptate, adipisci nostrum voluptates, possimus fugit rem beatae quaerat, velit nulla optio laboriosam consequatur vel dignissimos ad?</p>
                <a href="#">READ MORE</a>
            </div>
        </div>
       
    </div>
</template>

<script>
export default {

}
</script>

<style scoped lang='scss'>
    .box{
        height: 750px;
        background-image: url('../assets/images/Group-35-2x.png');
        background-repeat: no-repeat;
        background-position-x: 600px;
        background-position-y: -80px;
        background-size: 1100px;
        background-color: #fafafa;
        .container{

            width: 1200px;
            .info{
            width: 700px;
            padding-top: 150px;
            
                span{
                    color: lightgreen;
                    
                }
                #subtitle{
                    font-size: 20px;
                    letter-spacing: 10px;
                }
                h2{
                    font-size: 55px;
                }
                p{
                    margin: 40px 0;
                    font-size: 12px;
                    color: grey;
                };
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
        }
       
        
    }
</style>