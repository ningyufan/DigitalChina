<template>
    <div class="DigitalYS">
        <div class="back">
            <div class="block2">
                <div class="animate" data-ani="fadeInDown"  data-delay="1000">
                    <div class="box">
                        <div class="ys6" style="transform: rotateY(0deg) translateZ(400px);">
                            <img class="img6" src="../assets/images/ysblock/1.png">
                            <div class="text6">图片1</div>
                            <div class="img_6"><div class="text_all">图片1</div></div>
                        </div>
                        <div class="ys7" style="transform: rotateY(45deg) translateZ(400px);">
                            <img class="img7" src="../assets/images/ysblock/2.png">
                            <div class="text7">图片2</div>
                            <div class="img_7"><div class="text_all">图片2</div></div>
                        </div>
                        <div class="ys8" style="transform: rotateY(90deg) translateZ(400px);">
                            <img class="img8" src="../assets/images/ysblock/3.png">
                            <div class="text8">图片3</div>
                            <div class="img_8"><div class="text_all">图片3</div></div>
                        </div>
                        <div class="ys9" style="transform: rotateY(135deg) translateZ(400px);">
                            <img class="img9" src="../assets/images/ysblock/4.png">
                            <div class="text9">图片4</div>
                            <div class="img_9"><div class="text_all">图片4</div></div>
                        </div>
                        <div class="ys10" style="transform: rotateY(180deg) translateZ(400px);">
                            <img class="img10" src="../assets/images/ysblock/5.png">
                            <div class="text10">图片5</div>
                            <div class="img_10"><div class="text_all">图片5</div></div>
                        </div>
                        <div class="ys11" style="transform: rotateY(225deg) translateZ(400px);">
                            <img class="img11" src="../assets/images/ysblock/6.png">
                            <div class="text11">图片6</div>
                            <div class="img_11"><div class="text_all">图片6</div></div>
                        </div>
                        <div class="ys12" style="transform: rotateY(270deg) translateZ(400px);">
                            <img class="img12" src="../assets/images/ysblock/7.png">
                            <div class="text12">图片7</div>
                            <div class="img_12"><div class="text_all">图片7</div></div>
                        </div>
                        <div class="ys13" style="transform: rotateY(315deg) translateZ(400px);">
                            <img class="img13" src="../assets/images/ysblock/8.png">
                            <div class="text13">图片8</div>
                            <div class="img_13"><div class="text_all">图片8</div></div>
                        </div>
                    </div>
                </div>
                <!-- <div class="img_6"></div> -->
            </div>
        </div>
        <div class="back">
            <div class="block2">

            </div>
        </div>
        
    </div>
</template>

<script>
import animated from 'animate.css' 
export default {
    layout:'blank',
    methods: {
	  	handleAnimate() {
	  		let top = pageYOffset || document.documentElement.scrollTop || document.body.scrollTop;
	  		let vh = document.documentElement.clientHeight;
	  		let dom = document.querySelectorAll(".animate");
	  		[].slice.call(dom).forEach(v => {
	  			if(top + vh > v.offsetTop){
	  				var delay = v.dataset.delay;
	  				if(delay){
	  					setTimeout(() => {
	  						v.style.opacity = 1;
		  					v.classList.add(v.dataset.ani)
		  				}, delay)
	  				}else{
	  					v.style.opacity = 1;
	  					v.classList.add(v.dataset.ani)
	  				}
	  			}else{
	  				v.classList.remove(v.dataset.ani)
	  				v.style.opacity = 0;
	  			}
	  		})
 
	  	}
	  },
    mounted() {
    this.$nextTick(() => {
        this.handleAnimate()//初始化第一次加载时在视口内就执行动画
        addEventListener('scroll', this.handleScroll);
        addEventListener('scroll', this.handleAnimate);

    })
    
    },
    destroyed() {
    removeEventListener('scroll', this.handleScroll);//避免影响其他页面
    removeEventListener('scroll', this.handleAnimate);
    }
}
</script>

<style>
.DigitalYS{
    height: 100%;
    width: 100%;
}
.back{
    background-image: url(../assets/images/ysblock/background1.png);
    background-size: 100% 100%;
    height: 100vh;
}
.block2{
    background-image: url(../assets/images/ysblock/block2.png);
    background-size: 100% 100%;
    height: 98%;
    margin: auto 2.5% auto 3%;
    margin-bottom: 20px;
}
.img6:hover,.img7:hover,.img8:hover,.img9:hover,.img10:hover,.img11:hover,.img12:hover,.img13:hover{
    border: 2px solid white;
    -webkit-transform:scale(1.2);
	-webkit-box-shadow:0px 0px 30px #ccc;
    z-index: 3;
}
.img6,.img7,.img8,.img9,.img10,.img11,.img12,.img13{
    -webkit-transform:scale(1);
    -webkit-transition-duration: 0.5s;
    width:292px;
    height: 210px;
    z-index: 2;
    position: absolute;
}
.text6,.text7,.text8,.text8,.text9,.text10,.text11,.text12,.text13{
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
.ys6:hover .text6,.ys7:hover .text7,.ys8:hover .text8,.ys9:hover .text9,.ys10:hover .text10,.ys11:hover .text11,.ys12:hover .text12,.ys13:hover .text13{
    -webkit-transform:scale(1.2);
    opacity: 0;
}
.img_6,.img_7,.img_8,.img_9,.img_10,.img_11,.img_12,.img_13{
    background-image: url(../assets/images/ysblock/block4.png);
    background-size: 100% 100%;
    height: 40%;
    width: 100%;
    position: absolute;
    text-align: center;
    opacity: 0;
    transition: opacity 0.7s ease-in;
}
.ys6:hover .img_6,.ys7:hover .img_7,.ys8:hover .img_8,.ys9:hover .img_9,.ys10:hover .img_10,.ys11:hover .img_11,.ys12:hover .img_12,.ys13:hover .img_13{
    margin-top: 35vh;
    z-index: 3;
    opacity: 1;     
}
.text_all{
    height: 60%;
    width: 80%;
    margin-left: 10%;
    margin-top: 2.5vh
}
@keyframes fn{
    0% {transform:rotateX(-6deg) rotateY(0deg);}
    100%{transform:rotateX(-6deg) rotateY(360deg);}
}
.box{				
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
.box:hover{
    animation-play-state: paused;
}
.box>div{
    width:292px;
    height:200px;
    position: absolute;
    left:0;
    top:28vh;
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
