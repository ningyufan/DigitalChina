<template>
    <div class="gx_box1" aos = "zoom-in">
        <div class="tab">
				Smart City
			</div>
			<div class="con"  aos = "zoom-in">
				<div class="pic_style">
					<div class="img1"><img src="../../assets/images/gx/gxmap.png"  height="100%" width="100%" alt=""></div>
					<div class="img2"><img src="../../assets/images/gx/gxmap1.png"  height="100%" width="100%" alt=""></div>
				</div>
				<div class="cspic_list">
					<div class="cspic_list1">
						<div class="img1"><img src="../../assets/images/gx/nanning.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/nanning1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list2">
						<div class="img1"><img src="../../assets/images/gx/liuzhou.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/liuzhou1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list3">
						<div class="img1"><img src="../../assets/images/gx/guilin.png"  height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/guilin1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list4">
						<div class="img1"><img src="../../assets/images/gx/guigang.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/guigang1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list5">
						<div class="img1"><img src="../../assets/images/gx/qinzhou.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/qinzhou1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list6">
						<div class="img1"><img src="../../assets/images/gx/yulin.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/yulin1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list7">
						<div class="img1"><img src="../../assets/images/gx/yufengqu.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/yufengqu1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list8">
						<div class="img1"><img src="../../assets/images/gx/luzhaixian.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/luzhaixian1.png" height="100%" width="100%" alt=""></div>
					</div>
				</div>
            </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
/* 智慧城市 start */
.gx_box1 {
    width: 100vw;
    height: 60vh;
    background-image: url(../../assets/images/gx/bg1.png);
    background-size: 100% 100%;

}
.gx_box1 .tab {
    width: 100vw;
    height: 15vh;
    line-height: 15vh;
    text-align: center;
    font-size: 6vh;
    font-family: STXingkai;
    color: rgb(48, 189, 245);
    
}
.gx_box1 .tab:hover {
    animation: tab_scale 1s linear 3;
}

@keyframes tab_scale{
    33.3%{
        font-size: 5vh;
    }
    66.6%{
        font-size: 5.5vh;
    }
    99.9%{
        font-size: 5vh;
    }
}


.gx_box1 .con {
    height: 40vh;
    width: 80vw;
    margin: 0 auto;
    position: relative;
}
.gx_box1 .con .pic_style {
    width: 28vw;
    height: 40vh;
    position: absolute;
    left: 0;
    top: 0;
    transform-style: preserve-3d;
    transform: perspective(800px) rotateY(0deg);
}
.gx_box1 .con .pic_style .img1,
.gx_box1 .con .pic_style .img2{
    width: 28vw;
    height: 40vh;
    position: absolute;
    left:0;
    top: 0;
    backface-visibility: hidden;
    transform: perspective(800px) rotateY(0deg);
    transition: all 1s ease;
}
.gx_box1 .con .cspic_list{
    height: 40vh;
    width: 52vw;
    position: absolute;
    right: 0;  
}
.gx_box1 .con .cspic_list .cspic_list1{
    height: 20vh;
    width: 13vw;

    position: relative;
    transform-style: preserve-3d;
    transform: perspective(800px) rotateY(0deg);
}
.gx_box1 .con .cspic_list .cspic_list1 .img1,
.gx_box1 .con .cspic_list .cspic_list1 .img2{
    height: 20vh;
    width: 13vw;

    position: absolute;
    left:0;
    top: 0;
    backface-visibility: hidden;
    transform: perspective(800px) rotateY(0deg);
    transition: all 1s ease;
}
.gx_box1 .con .cspic_list .cspic_list2 .img1,
.gx_box1 .con .cspic_list .cspic_list2 .img2{
    height: 20vh;
    width: 13vw;
    position: absolute;
    left:13vw;
    top: 0;
    backface-visibility: hidden;
    transform: perspective(800px) rotateY(0deg);
    transition: all 1s ease;
}
.gx_box1 .con .cspic_list .cspic_list3 .img1,
.gx_box1 .con .cspic_list .cspic_list3 .img2{
    height: 20vh;
    width: 13vw;
    position: absolute;
    left:26vw;
    top: 0;
    backface-visibility: hidden;
    transform: perspective(800px) rotateY(0deg);
    transition: all 1s ease;
}
.gx_box1 .con .cspic_list .cspic_list4 .img1,
.gx_box1 .con .cspic_list .cspic_list4 .img2{
    height: 20vh;
    width: 13vw;
    position: absolute;
    left:38vw;
    top: 0;
    backface-visibility: hidden;
    transform: perspective(800px) rotateY(0deg);
    transition: all 1s ease;
}
.gx_box1 .con .cspic_list .cspic_list5 .img1,
.gx_box1 .con .cspic_list .cspic_list5 .img2{
    height: 20vh;
    width: 13vw;
    position: absolute;
    left:0vw;
    bottom: 0;
    backface-visibility: hidden;
    transform: perspective(800px) rotateY(0deg);
    transition: all 1s ease;
}
.gx_box1 .con .cspic_list .cspic_list6 .img1,
.gx_box1 .con .cspic_list .cspic_list6 .img2{
    height: 20vh;
    width: 13vw;
    position: absolute;
    left:13vw;
    bottom: 0;
    backface-visibility: hidden;
    transform: perspective(800px) rotateY(0deg);
    transition: all 1s ease;
}
.gx_box1 .con .cspic_list .cspic_list7 .img1,
.gx_box1 .con .cspic_list .cspic_list7 .img2{
    height: 20vh;
    width: 13vw;
    position: absolute;
    left:26vw;
    bottom: 0;
    backface-visibility: hidden;
    transform: perspective(800px) rotateY(0deg);
    transition: all 1s ease;
}
.gx_box1 .con .cspic_list .cspic_list8 .img1,
.gx_box1 .con .cspic_list .cspic_list8 .img2{
    height: 20vh;
    width: 13vw;
    position: absolute;
    left:38vw;
    bottom: 0;
    backface-visibility: hidden;
    transform: perspective(800px) rotateY(0deg);
    transition: all 500ms ease;
}

.gx_box1 .con .cspic_list .cspic_list1 .img2,
.gx_box1 .con .cspic_list .cspic_list2 .img2,
.gx_box1 .con .cspic_list .cspic_list3 .img2,
.gx_box1 .con .cspic_list .cspic_list4 .img2,
.gx_box1 .con .cspic_list .cspic_list5 .img2,
.gx_box1 .con .cspic_list .cspic_list6 .img2,
.gx_box1 .con .cspic_list .cspic_list7 .img2,
.gx_box1 .con .cspic_list .cspic_list8 .img2,
.gx_box1 .con .pic_style .img2 {
    transform: translateZ(2px) rotateY(180deg);
}
.gx_box1 .con .cspic_list .cspic_list1:hover .img1,
.gx_box1 .con .cspic_list .cspic_list2:hover .img1,
.gx_box1 .con .cspic_list .cspic_list3:hover .img1,
.gx_box1 .con .cspic_list .cspic_list4:hover .img1,
.gx_box1 .con .cspic_list .cspic_list5:hover .img1,
.gx_box1 .con .cspic_list .cspic_list6:hover .img1,
.gx_box1 .con .cspic_list .cspic_list7:hover .img1,
.gx_box1 .con .cspic_list .cspic_list8:hover .img1,
.gx_box1 .con .pic_style:hover .img1{
    transform: perspective(800px) rotateY(180deg)
}
.gx_box1 .con .cspic_list .cspic_list1:hover .img2,
.gx_box1 .con .cspic_list .cspic_list2:hover .img2,
.gx_box1 .con .cspic_list .cspic_list3:hover .img2,
.gx_box1 .con .cspic_list .cspic_list4:hover .img2,
.gx_box1 .con .cspic_list .cspic_list5:hover .img2,
.gx_box1 .con .cspic_list .cspic_list6:hover .img2,
.gx_box1 .con .cspic_list .cspic_list7:hover .img2,
.gx_box1 .con .cspic_list .cspic_list8:hover .img2,
.gx_box1 .con .pic_style:hover .img2 {
    transform: perspective(800px) rotateY(0deg)
}
/* 智慧城市 end */
</style>