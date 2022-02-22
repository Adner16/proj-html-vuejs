<template>
<div class="background">
    <div class="filter">
        <div class="container">
            <span class="virgolette">"</span>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolor provident aperiam laudantium ratione, error aliquam tempora tenetur magni amet fugiat itaque earum dolores quos, dignissimos impedit eveniet repellendus labore accusantium!</p>
            <div class="image">
            </div>
            <span class="name">LISSA DURBIN</span><br>
            <span>client</span>
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
        height: 600px;
        background-image: url('../assets/images/four-businesspeople-in-a-boardroom-with-paperwork-PC4V8H4.jpg');
        background-position: center;
        background-repeat: no-repeat;
        background-size: cover;
        .filter{
            height: 600px;
            background-color: rgba($color: black, $alpha: 0.8);
            .container{
                width: 800px;
                height: 600px;
                display: flex;
                flex-direction: column;
                justify-content: center;
                align-items: center;
                text-align: center;
                color: white;
                .virgolette{
                    font-size: 100px;
                    color: lightgreen;
                }
                p{
                    font-size: 20px;
                    line-height: 40px;
                }
                .image{
                    margin-top: 30px;
                    margin-bottom: 20px;
                    width: 90px;
                    height: 90px;
                    border-radius: 50%;
                    overflow: hidden;
                    background-image: url('../assets/images/businesswoman-analysing-document-P8WSNMC-1024x820.jpg');
                    background-position: center;
                    background-size: cover;
                    background-repeat: no-repeat;   
                }
                .name{
                    color: lightgreen;
                }

            }
        }
    }
</style>