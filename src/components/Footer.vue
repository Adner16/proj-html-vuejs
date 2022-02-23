<template>
<div>
    <footer>
        <div class="row">
            <div class="col-3">
                <div class="image">
                    <img class="img-fluid" src="../assets/images/cropped-Group-39-2x.png" alt="">
                </div>
                <p class="grey">Lorem, ipsum dolor sit amet consectetur adipisicing elit. Tempora vel sequi enim, nisi sint a minima voluptatum at quae dicta soluta quibusdam consequatur natus ducimus eius? Aperiam minus sequi eligendi?</p>
            </div>
            <div class="col-3">
                <h5>Quick Links</h5>
                <ul>
                    <li v-for="(item,index) in items" :key='index'>
                        <a href="">{{item.name}}</a>
                    </li>
                     <!-- <li>
                        <a href="">careers</a>
                    </li>
                     <li>
                        <a href="">careers</a>
                    </li>
                     <li>
                        <a href="">careers</a>
                    </li>
                     <li>
                        <a href="">careers</a>
                    </li>
                     <li>
                        <a href="">careers</a>
                    </li> -->
                </ul>
            </div>
            <div class="col-3">
                <h5>Contacts</h5>
                <p class="grey">londra, via garibaldi 56</p>
                <p class="grey">infi.yourdomain.com</p>
                <p class="grey">+99 020 44556262</p>
            </div>
            <div class="col-3">
                <h5>Location Map</h5>
                <div class="map">
                    <img src="../assets/images/map.png" class="img-fluid" alt="">
                </div>
            </div>
        </div>
    </footer>
    <div class="bottom-footer">
        <div class="container-footer">
            <span class="grey">2020PHLOXBUSINESSTHEME</span>
        </div> 
    </div>
</div>
    
</template>

<script>
export default {

}
</script>

<style scoped lang='scss'>
     .grey{
            font-size: 12px;
            color: grey;
        }
        .bottom-footer{
            background-color: black;
            .container-footer{
                width: 1200px;
                margin: auto;
            }
            span{
                line-height: 100px;
            }
        }
    footer{
        width: 1200px;
        margin: auto;
        margin-top: 100px;
        margin-bottom: 100px;
        h5{
            margin-bottom: 30px;
        }
        .image{
            width: 200px;
            margin-bottom: 20px;
        }
       
        ul{
            list-style-type: none;
            padding-left: 5px;
            li a{
                text-decoration: none;
                font-size: 12px;
                color: grey;
            }
        };
    }
</style>