<template>
    <div class="background d-flex">
        <div class="container">
            <div class="row row-size">
                <div class="col-3 description">
                    <h2>with <span class="green">Live Chat</span><br><span class="green">24/7</span> Support</h2>
                    <p class="grey">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eos porro, necessitatibus maxime pariatur asperiores repellat ducimus cumque! Qui accusantium eligendi debitis unde odit molestiae provident, nihil, modi porro voluptas rerum.</p>
                </div>
                <div class="col-9">
                    <div class="container-fluid">
                        <div class="row">
                            <div class="col-3 card">
                                <div class="box-white">
                                    <h5 class="mb-0">DESIGNING</h5>
                                    <p class="grey mb-0 mt-2">all design</p>
                                </div>
                                <div class="black-box">
                                    <p>$ <span><span class="number">13</span>/Design</span></p>
                                </div>
                                <div class="box-white">
                                    <i></i><span>Creative Design Enabled</span>
                                    <i></i><span>Vibrant color usage</span>
                                    <i></i><span>Eye catching design</span>
                                    <i></i><span>Extreme typography</span>
                                    <i></i><span>Exceptional design</span>
                                </div>
                            </div>
                            <div class="col-3 card">
                                <div class="box-white">
                                    <h5 class="mb-0">DESIGNING</h5>
                                    <p class="grey mb-0 mt-2">all design</p>
                                </div>
                                <div class="black-box">
                                    <p>$ <span><span class="number">13</span>/Design</span></p>
                                </div>                                
                                <div class="box-white">
                                    <i></i><span>Creative Design Enabled</span>
                                    <i></i><span>Vibrant color usage</span>
                                    <i></i><span>Eye catching design</span>
                                    <i></i><span>Extreme typography</span>
                                    <i></i><span>Exceptional design</span>
                                </div>
                            </div>
                            <div class="col-3 card">
                                <div class="box-white">
                                    <h5 class="mb-0">DESIGNING</h5>
                                    <p class="grey mb-0 mt-2">all design</p>
                                </div>
                                <div class="black-box">
                                    <p>$ <span><span class="number">13</span>/Design</span></p>
                                </div>
                                <div class="box-white">
                                    <i></i><span>Creative Design Enabled</span>
                                    <i></i><span>Vibrant color usage</span>
                                    <i></i><span>Eye catching design</span>
                                    <i></i><span>Extreme typography</span>
                                    <i></i><span>Exceptional design</span>
                                </div>
                            </div>
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
.background{
    height: 700px;
    background-color: #fafafa;
    .container{
        width: 1200px;
        margin: auto;
        .row-size{
            // height: 600px;
            h2{
                margin-bottom: 50px;
                margin-top: 120px;
            }
            .grey{
                font-size: 12px;
                color: grey;
            }
            .green{
                color: lightgreen;
            }
            .card{
                background-color: black;
                padding: 0;
                padding-top: 20px;
                border: 0;
                box-shadow: 0 0 30px grey;
                margin: 20px;
                border-radius:20px ;

                .box-white{
                    display: flex;
                    flex-direction:column;
                    align-items: center;
                    justify-content: center;
                    background-color: white;
                    padding:30px 20px;
                    span{
                        font-size: 13px;
                        margin: 5px 0;
                        color: grey;
                    }
                }
                .black-box{
                    padding:20px;
                    color: white;
                    display: flex;
                    justify-content: center;
                    align-items: center;
                    p{
                        margin-bottom:0 ;
                    }
                    .number{
                        font-size: 35px;
                    }
                }
            }
        }
    }   
}

</style>