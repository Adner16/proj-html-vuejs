<template>
<div class="box">
    <div id="top-header" class="d-flex justify-content-between align-items-center container-fluid ">
        <span><i></i>(001) 88451234     88455438</span>
        <div id="icons">
            <i></i>
            <i></i>
            <i></i>
        </div>
    </div>
    <nav class="container-fluid d-flex justify-content-between align-items-center">
        <div id="left-buttons">
            <a href="#"><img src="../assets/images/cropped-Group-39-2x.png" alt=""></a>
        </div>
        <div id="navbar" class="d-flex flex-row">
            <div v-for="(item,index) in items" :key='index'>
                <a href="#">{{item}}</a>
            </div>
            <!-- <div>
                <a href="#">ABOUT</a>
            </div>
            <div>
                <a href="#">SERVICES</a>
            </div>
            <div>
                <a href="#">SHOWCASE</a>
            </div>
            <div>
                <a href="#">BLOG</a>
            </div>
            <div>
                <a href="#">CONTACT</a>
            </div>-->
        </div>
        <div id="right-buttons">
            <a href="#" class="active">PURCHASE</a>
            <i></i>
        </div>
    </nav>
</div>

</template>
    
<script>
export default {

}
</script>

<style scoped lang='scss'>
.box{
    #top-header{
            height: 40px;
            background-color: #3c3c3c;
            color: white;
        }
    nav {
        height: 100px;
        #navbar a{
            text-decoration: none;
            color: black;
            font-size: 0.9em;
            margin: 0 20px
        }
        #right-buttons a{
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
    
</style>