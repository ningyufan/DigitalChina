<template>
    <div class="gx_box6">
        <div class="tab" aos = "zoom-in">
            数字广西
        </div>
        <div class="box6_con" aos = "zoom-in-down">
                <div class="con_nav1">数字政府
                     <ul class="ul1">
                        <li><a href="/gx_content1" target="_blank">一图看懂数字广西建设大会</a></li>
                        <li><a href="/gx_content2" target="_blank">广西数字政务一体化平台“一窗通”上线试运行 全面提升开办企业效率</a></li>
                        <li><a href="/gx_content3" target="_blank">结伴相行 合力攻坚——全区政务数据“聚通用”攻坚在行动</a></li>
                    </ul>
                </div>
                <div class="con_nav2">数字社会
                    <ul class="ul2">
                        <li><a href="/gx_content4" target="_blank">广西将实施“壮美广西·智慧广电”工程</a></li>
                        <li><a href="/gx_content5" target="_blank">“五一”旅游新体验：广西最美海岛开通移动5G网络</a></li>
                        <li><a href="/gx_content6" target="_blank">全国首个5G华为数字小镇在钦州启动</a></li>
                    </ul>
                </div>
                <div class="con_nav3">数字经济
                    <ul class="ul3">
                        <li><a href="/gx_content7" target="_blank">“数字+”赋能广西经济和社会高质量发展</a></li>
                        <li><a href="/gx_content9" target="_blank">打造数字经济龙头企业引领数字广西建设新发展</a></li>
                        <li><a href="/gx_content8" target="_blank">中国携手东盟加速拥抱数字经济</a></li>
                    </ul>
                </div>

        
               
    
                
        
                
        </div>
    </div>
</template>

<script>
export default {
}
</script>

<style>
.gx_box6 {
    width: 100vw;
    height: 100vh;
    background-image: url(../../assets/images/gx/bg7.jpg);
    background-size: 100% 100%; 
    
}
.gx_box6 .tab {
    width: 100vw;
    height: 15vh;
    line-height: 15vh;
    text-align: center;
    font-size: 6vh;
    font-family: STXingkai;
    color: rgb(48, 189, 245);
    
}
.gx_box6 .tab:hover {
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
.gx_box6 .box6_con {
    width: 80vw;
    height: 80vh;
    margin: 0 auto;
    background-color: rgba(0, 0, 0,0.5);
    box-shadow: 2vh 1vw 5px black;
    position: relative;
    background-image: url(../../assets/images/gx/box7_bgpic.png);
    background-size: 100% 100%;
}

.gx_box6 .box6_con .con_nav1{
    position: absolute;
    top: 8vh;
    z-index: 2;
    float: left;
    left: 10%;

}
.gx_box6 .box6_con .con_nav2{
    position: absolute;
    left: 10%;
    top: 28vh;
    
    
}
.gx_box6 .box6_con .con_nav3{
    position: absolute;
    left: 10%;
    top: 49vh;
}
.gx_box6 .box6_con .con_nav1,
.gx_box6 .box6_con .con_nav2,
.gx_box6 .box6_con .con_nav3{
    height: 20vh;
    width: 21vw;
    margin: 2vh auto;
    line-height: 14vh;
    font-size: 4vh;
    color:white
}

.gx_box6 .box6_con .ul1{
   position: absolute;
   left: 20vw;
   top: -3vh;
}
.gx_box6 .box6_con .ul2{
   position: absolute;
   left: 20vw;
   top: -2vh;
}
.gx_box6 .box6_con .ul3{
   position: absolute;
   left: 20vw;
   top: -2vh;
}
/* .gx_box6 .box6_con  .con_nav3:hover ul{
    transform: scale(1.1,1.1);
    color: aqua;
} */
.gx_box6 .box6_con ul {
    width: 50vw;
    height: 30%;
    position: absolute;
    float: left;

}
.gx_box6 .box6_con li {
    margin: 0;
    width: 50vw;
    line-height: 7vh;
    font-size: 3vh;
    list-style-image: url(../../assets/images/gx/list_style.png);
    background-size: 100% 100%;
    float: left;
    
}
.gx_box6 .box6_con .con_nav1:hover{
    color: aqua;
}
.gx_box6 .box6_con .con_nav1:hover a{
    color: aqua;
}
.gx_box6 .box6_con .con_nav2:hover{
    color: aqua;
}
.gx_box6 .box6_con .con_nav2:hover a{
    color: aqua;
}
.gx_box6 .box6_con .con_nav3:hover{
    color: aqua;
}
.gx_box6 .box6_con .con_nav3:hover a{
    color: aqua;
}
</style>