<template>
    <div class="DigitalYS">
        <div class="back">
            <div class="block2">
                <div class="animate" data-ani="fadeInDown"   data-delay="1000">
                    <div class="box">
                        <div style="transform: rotateY(0deg) translateZ(400px);">
                            <img class="img6" src="../assets/images/ysblock/1.png">
                        </div>
                        <div style="transform: rotateY(45deg) translateZ(400px);">
                            <img class="img7" src="../assets/images/ysblock/2.png">
                        </div>
                        <div style="transform: rotateY(90deg) translateZ(400px);">
                            <img class="img8" src="../assets/images/ysblock/3.png">
                        </div>
                        <div style="transform: rotateY(135deg) translateZ(400px);">
                            <img class="img9" src="../assets/images/ysblock/4.png">
                        </div>
                        <div style="transform: rotateY(180deg) translateZ(400px);">
                            <img class="img10" src="../assets/images/ysblock/5.png">
                        </div>
                        <div style="transform: rotateY(225deg) translateZ(400px);">
                            <img class="img11" src="../assets/images/ysblock/6.png">
                        </div>
                        <div style="transform: rotateY(270deg) translateZ(400px);">
                            <img class="img12" src="../assets/images/ysblock/7.png">
                        </div>
                        <div style="transform: rotateY(315deg) translateZ(400px);">
                            <img class="img13" src="../assets/images/ysblock/8.png">
                        </div>
                    </div>
                </div>
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
    position: relative;
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
