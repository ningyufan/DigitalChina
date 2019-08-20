<template>
    <div class="back_ys">
        <div class="block2_ys">
            <br><br><br>
            <div class="titel1_ys">大数据——学生风采</div>
            <div class="animate" data-ani="fadeInDown"  data-delay="1000">
                <div class="box_ys">
                    <div class="ys6_ys" style="transform: rotateY(0deg) translateZ(400px);">
                        <img class="img6_ys" src="@/assets/images/ysblock/1.png">
                        <div class="text6_ys">图片1</div>
                        <div class="img_6_ys"><div class="text_all_ys">图片1</div></div>
                    </div>
                    <div class="ys7_ys" style="transform: rotateY(45deg) translateZ(400px);">
                        <img class="img7_ys" src="@/assets/images/ysblock/2.png">
                        <div class="text7_ys">图片2</div>
                        <div class="img_7_ys"><div class="text_all_ys">图片2</div></div>
                    </div>
                    <div class="ys8" style="transform: rotateY(90deg) translateZ(400px);">
                        <img class="img8_ys" src="@/assets/images/ysblock/3.png">
                        <div class="text8_ys">图片3</div>
                        <div class="img_8_ys"><div class="text_all_ys">图片3</div></div>
                    </div>
                    <div class="ys9" style="transform: rotateY(135deg) translateZ(400px);">
                        <img class="img9_ys" src="@/assets/images/ysblock/4.png">
                        <div class="text9_ys">图片4</div>
                        <div class="img_9_ys"><div class="text_all_ys">图片4</div></div>
                    </div>
                    <div class="ys10_ys" style="transform: rotateY(180deg) translateZ(400px);">
                        <img class="img10_ys" src="@/assets/images/ysblock/5.png">
                        <div class="text10_ys">图片5</div>
                        <div class="img_10_ys"><div class="text_all_ys">图片5</div></div>
                    </div>
                    <div class="ys11_ys" style="transform: rotateY(225deg) translateZ(400px);">
                        <img class="img11_ys" src="@/assets/images/ysblock/6.png">
                        <div class="text11_ys">图片6</div>
                        <div class="img_11_ys"><div class="text_all_ys">图片6</div></div>
                    </div>
                    <div class="ys12_ys" style="transform: rotateY(270deg) translateZ(400px);">
                        <img class="img12_ys" src="@/assets/images/ysblock/7.png">
                        <div class="text12_ys">图片7</div>
                        <div class="img_12_ys"><div class="text_all_ys">图片7</div></div>
                    </div>
                    <div class="ys13_ys" style="transform: rotateY(315deg) translateZ(400px);">
                        <img class="img13_ys" src="@/assets/images/ysblock/8.png">
                        <div class="text13_ys">图片8</div>
                        <div class="img_13_ys"><div class="text_all_ys">图片8</div></div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import animated from 'animate.css' 
export default {
     head:{
        script:[
            {src:'js/jquery.1.7.1.min.js'},
            {src:'js/aos.js'},
        ],
        link: [
            { rel: 'stylesheet', href: 'css/normalize.css' },
            { rel: 'stylesheet', href: 'css/demo.css' },
            { rel: 'stylesheet', href: 'js/aos.css' },
            { rel: 'stylesheet', href: 'css/styles.css' }
        ]
    },
    mounted(){
        AOS.init({
            easing: 'ease-out-back',
            duration: 1000
        });
    }
}
</script>

<style>
.back_ys{
    background-image: url(../assets/images/ysblock/background1.png);
    background-size: 100% 100%;
    height: 100vh;
}
.block2_ys{
    background-image: url(../assets/images/ysblock/block2.png);
    background-size: 100% 100%;
    height: 98%;
    margin: auto 2.5% auto 3%;
    margin-bottom: 20px;
}
.img6_ys:hover,.img7_ys:hover,.img8_ys:hover,.img9_ys:hover,.img10_ys:hover,.img11_ys:hover,.img12_ys:hover,.img13_ys:hover{
    border: 2px solid white;
    -webkit-transform:scale(1.2);
	-webkit-box-shadow:0px 0px 30px #ccc;
    z-index: 3;
}
.img6_ys,.img7_ys,.img8_ys,.img9_ys,.img10_ys,.img11_ys,.img12_ys,.img13_ys{
    -webkit-transform:scale(1);
    -webkit-transition-duration: 0.5s;
    width:292px;
    height: 210px;
    z-index: 2;
    position: absolute;
}
.text6_ys,.text7_ys,.text8_ys,.text9_ys,.text10_ys,.text11_ys,.text12_ys,.text13_ys{
    position: relative;
    z-index: 3;
    top: 150px;
    text-align: center;
    color: white;
    -webkit-transform:scale(1);
    -webkit-transition-duration: 0.5s;
    transition: opacity 0.7s ease-in;
    opacity: 1;
}
.ys6_ys:hover .text6_ys,.ys7_ys:hover .text7_ys,.ys8_ys:hover .text8_ys,.ys9_ys:hover .text9_ys,.ys10_ys:hover .text10_ys,.ys11_ys:hover .text11_ys,.ys12_ys:hover .text12_ys,.ys13_ys:hover .text13_ys{
    -webkit-transform:scale(1.2);
    opacity: 0;
}
.img_6_ys,.img_7_ys,.img_8_ys,.img_9_ys,.img_10_ys,.img_11_ys,.img_12_ys,.img_13_ys{
    background-image: url(../assets/images/ysblock/block4.png);
    background-size: 100% 100%;
    height: 40%;
    width: 100%;
    position: absolute;
    text-align: center;
    opacity: 0;
    transition: opacity 0.7s ease-in;
}
.ys6_ys:hover .img_6_ys,.ys7_ys:hover .img_7_ys,.ys8_ys:hover .img_8_ys,.ys9_ys:hover .img_9_ys,.ys10_ys:hover .img_10,.ys11_ys:hover .img_11_ys,.ys12_ys:hover .img_12_ys,.ys13_ys:hover .img_13_ys{
    margin-top: 35vh;
    z-index: 3;
    opacity: 1;     
}
.text_all_ys{
    height: 60%;
    width: 80%;
    margin-left: 10%;
    margin-top: 2.5vh
}
@keyframes fn{
    0% {transform:rotateX(-6deg) rotateY(0deg);}
    100%{transform:rotateX(-6deg) rotateY(360deg);}
}
.box_ys{				
    width:292px;
    height:200px;
    position:relative;
    margin:auto;
    transform-style:preserve-3d;
    transform:rotateX(-10deg);
    animation: fn 10s;
    animation-iteration-count: infinite;
    animation-timing-function: linear;
    /* animation-delay: 10s; */
}
.box_ys:hover{
    animation-play-state: paused;
}
.box_ys>div{
    width:292px;
    height:200px;
    position: absolute;
    left:0;
    top:17vh;
}
.fadeInUpBig{
    animation: fadeInUpBig 1s;
}
.rollIn{
    animation: rollIn 1s;
}
.slideInRight{
    animation: slideInRight 1s;
}
.bounceInLeft{
    animation: bounceInLeft 2s ease-in;
}
.bounceInRight{
    animation: zoomIn 2s ease-in;
}
.fadeInDown{
    animation: fadeInDown 2s ease-in;
}
</style>