<template>
<div class="background">
    <div class="container">
      <div class="row">
          <div class="col-7">
                <div class="image">
                    <img src="../assets/images/businesswoman-analysing-document-P8WSNMC-1024x820.jpg" class="img-fluid" alt="">
                </div>
              
          </div>
          <div class="col-5 d-flex flex-column align-items-start justify-content-center">
              <h2>Learn more <br> about our <br><span>mission</span></h2>
              <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa eveniet, provident recusandae natus deleniti veniam tempora minus nam placeat impedit quod optio cum asperiores eius cumque molestias illo, quas aperiam?</p>
              <div class="btn">
                  <a href="#">READ MORE</a>
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
.background{
background-color: #fafafa;
height: 650px;
background-image: url('../assets/images/busy-architect-PYVKWM4-1024x872.jpg');
background-repeat: no-repeat;
background-size:450px ;
background-position-y: 100px;
display: flex;
align-items: center;
    .container{
        width: 1200px;
        margin: auto;
        .image{
            width: 400px;
            height: 350px;
        }
        .col-5 {
            span{
                color: lightgreen;
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
    }
}   
</style>