<template>
    <div class="DigitalYS">
        <div class="header_one">
            <div class="header " id="header" >
                <div class="logo">
                    <a href="#">
                        Digital <img src="../assets/images/logo.png" height="30vh" width="30vw" alt=""> China
                    </a>
                </div>
                <div class=" fixed-width clearfix" :class="{fixed: isFixed}">
                    <div class="header-title fl" style="text-align: center">
                        <div class="header_nav">
                        <el-row class="row_one">
                            <div class="ce_nav">
                                <a href="#">
                                    <i class="el-icon-star-on">中</i>
                                </a>
                                <a href="#">
                                    <i class="el-icon-star-off">英</i>
                                </a>
                            </div>
                        </el-row>
                        <el-row class="row_tow">
                            <div class="nav">
                                <ul>
                                    <nuxt-link to="/chinese_index"><li>首页</li></nuxt-link>
                                    <nuxt-link to="/Digital_China"><li>数字中国</li></nuxt-link>
                                    <nuxt-link to="/DigitalGX"><li>数字广西</li></nuxt-link>
                                    <nuxt-link to="/DigitalYL"><li>数字玉林</li></nuxt-link>
                                    <nuxt-link to="#"><li><div class="nav_5">数字玉师</div></li></nuxt-link>
                                    <nuxt-link to="/aboutMe"><li>关于我们</li></nuxt-link>
                                </ul>
                            </div>
                        </el-row>
                        </div>
                    </div>
                </div>
                <div class="YS">
                    <div class="row_ys">    
                        <div class="one_ys" >
                            <div class="box1_ys">
                                <div class="ys1_ys">
                                    <a href="#"><img src="../assets/images/ysblock/ys1.png" class="img1_ys" height="100%" width="100%"></a>
                                    <a href="#"><div class="text1_ys">玉林师范学院——曙光大数据应用创新中心揭牌成立</div></a>
                                    <div class="line1_ys"></div>
                                </div>
                                <div class="ys2_ys">
                                    <a href="#"><img src="../assets/images/ysblock/ys2.png" class="img2_ys" height="100%" width="100%"></a>
                                    <a href="#"><div class="text2_ys">计算机学院积极推进“玉林师范学院——曙光大数据学院”的建设</div></a>
                                    <div class="line2_ys"></div>
                                </div>
                                <div class="ys3_ys">
                                    <a href="#"><img src="../assets/images/ysblock/ys3.png" class="img3_ys" height="100%" width="100%"></a>
                                    <a href="#"><div class="text3_ys">学校举行市校共建玉林市大数据研究院揭牌仪式暨签约仪式</div></a>
                                    <div class="line3_ys"></div>
                                </div>
                                <div class="ys4_ys">
                                    <a href="#"><img src="../assets/images/ysblock/ys4.png" class="img4_ys" height="100%" width="100%"></a>
                                    <a href="#"><div class="text4_ys">曙光集团莅临大数据学院开展曙光大数据平台使用培训会</div></a>
                                    <div class="line4_ys"></div>
                                </div>
                                <div class="ys5_ys">
                                    <a href="#"><img src="../assets/images/ysblock/ys5.png" class="img5_ys" height="100%" width="100%"></a>
                                    <a href="#"><div class="text5_ys">学校领导到大数据应用创新中心（暨大数据学院）指导工作</div></a>
                                    <div class="line5_ys"></div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    
        <div class="back1_ys">
            <br>
            <div class="titel1_ys" aos="fade-up">titel1</div>
            <br>
            <div class="code1_ys" aos="fade-right">
                <img src="../assets/images/ysblock/ys4.png" class="img14_ys" height="100%" width="50%">
                <div class="text_14_ys">图片</div>
                <div class="color1_ys"></div>
            </div>
            <br>
            <div class="code2_ys" aos="fade-left">
                <img src="../assets/images/ysblock/ys4.png" class="img15_ys" height="100%" width="50%">
                <div class="text_15_ys">图片</div>
                <div class="color2_ys"></div>
            </div>
            <br>        
        </div>

        <div class="back_ys">
            <div class="block2_ys">
                <br><br><br>
                <div class="titel1_ys">titel1</div>
                <div class="animate" data-ani="fadeInDown"  data-delay="1000">
                    <div class="box_ys">
                        <div class="ys6_ys" style="transform: rotateY(0deg) translateZ(400px);">
                            <img class="img6_ys" src="../assets/images/ysblock/1.png">
                            <div class="text6_ys">图片1</div>
                            <div class="img_6_ys"><div class="text_all_ys">图片1</div></div>
                        </div>
                        <div class="ys7_ys" style="transform: rotateY(45deg) translateZ(400px);">
                            <img class="img7_ys" src="../assets/images/ysblock/2.png">
                            <div class="text7_ys">图片2</div>
                            <div class="img_7_ys"><div class="text_all_ys">图片2</div></div>
                        </div>
                        <div class="ys8" style="transform: rotateY(90deg) translateZ(400px);">
                            <img class="img8_ys" src="../assets/images/ysblock/3.png">
                            <div class="text8_ys">图片3</div>
                            <div class="img_8_ys"><div class="text_all_ys">图片3</div></div>
                        </div>
                        <div class="ys9" style="transform: rotateY(135deg) translateZ(400px);">
                            <img class="img9_ys" src="../assets/images/ysblock/4.png">
                            <div class="text9_ys">图片4</div>
                            <div class="img_9_ys"><div class="text_all_ys">图片4</div></div>
                        </div>
                        <div class="ys10_ys" style="transform: rotateY(180deg) translateZ(400px);">
                            <img class="img10_ys" src="../assets/images/ysblock/5.png">
                            <div class="text10_ys">图片5</div>
                            <div class="img_10_ys"><div class="text_all_ys">图片5</div></div>
                        </div>
                        <div class="ys11_ys" style="transform: rotateY(225deg) translateZ(400px);">
                            <img class="img11_ys" src="../assets/images/ysblock/6.png">
                            <div class="text11_ys">图片6</div>
                            <div class="img_11_ys"><div class="text_all_ys">图片6</div></div>
                        </div>
                        <div class="ys12_ys" style="transform: rotateY(270deg) translateZ(400px);">
                            <img class="img12_ys" src="../assets/images/ysblock/7.png">
                            <div class="text12_ys">图片7</div>
                            <div class="img_12_ys"><div class="text_all_ys">图片7</div></div>
                        </div>
                        <div class="ys13_ys" style="transform: rotateY(315deg) translateZ(400px);">
                            <img class="img13_ys" src="../assets/images/ysblock/8.png">
                            <div class="text13_ys">图片8</div>
                            <div class="img_13_ys"><div class="text_all_ys">图片8</div></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <div class="footer">footer</div>
    </div>
</template>

<script>
import animated from 'animate.css' 
export default {
    data () {
        return {
            isFixed: 0,
        }
    },
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
    methods: {
    handleScroll() {
        let top = pageYOffset || document.documentElement.scrollTop || document.body.scrollTop;
        if(top > 250){
            this.isFixed = 1;
        }else if(top < 200){
            this.isFixed = 0;
        }
    },
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

        },
        nav(idx){
            this.nav_lock = idx
        }
    },
    mounted() {
    AOS.init({
        easing: 'ease-out-back',
        duration: 1000
    });
    this.$nextTick(() => {
        this.handleAnimate()//初始化第一次加载时在视口内就执行动画
        addEventListener('scroll', this.handleScroll);
        addEventListener('scroll', this.handleAnimate);

    })
    
    },
    destroyed() {
    removeEventListener('scroll', this.handleScroll);//避免影响其他页面
    removeEventListener('scroll', this.handleAnimate);
    },
}
</script>

<style>
@import "@/assets/css/index/page_index.css";
.DigitalYS{
    width: 100%;
}
.nav_5{
    background-image: url('../assets/images/bg_xuanzhong.png');
    background-size: 100% 7.5vh ;
}
.nav:hover .nav_5{
    background: none;
}
.YS{
    color: white;
    width: 80%;
    margin-left: 10%
}
.one_ys{
    width: 70%;
    background-image: url(../assets/images/ysblock/block.png);
    background-size: 100% 100%;
    border: 2px solid transparent;
    height: 60vh;
    margin-left: -4%;
    margin-top: 4vh
}
.tow_ys{
    width: 30%;
    height: 100%;
}
.box1_ys{
    height: 82%;
    width: 72%;
    text-align: center;
    margin-top: 3.8vh;
    margin-left: 15%;
    /* border: 1px solid red; */
}
.ys1_ys{
    height: 60%;
    width: 62%;
    float: left;
}
.img1_ys{
    height: 100%;
    width: 100%;
    float: left;
}
.text1_ys{
    color: white;
    margin-left: 196.5%;
    margin-top: 3vh;
    height: 8%;
    width: 72%;
    -webkit-transform:scale(1);
    -webkit-transition-duration: 0.5s;
    font-size: 14px;
    z-index: 2;
}
.line1_ys{
    background-image: url(../assets/images/ysblock/line1.png);
    background-size: 100% 100%;
    height: 22%;
    width: 100%;
    margin-left: 180%;
    margin-top: -2.3vh;
}
.ys2_ys{
    height: 29.5%;
    width: 37%;
    float: right;
}
.img2_ys{
    height: 100%;
    width: 100%;
    float: right;
}
.text2_ys{
    position: absolute;
    color: white;
    margin-left: 29%;
    float: left;
    margin-top: 12vh;
    height: 8%;
    width: 23%;
    -webkit-transform:scale(1);
    -webkit-transition-duration: 0.5s;
    font-size: 14px;
}
.line2_ys{
    background-image: url(../assets/images/ysblock/line1.png);
    background-size: 100% 100%;
    height: 45%;
    width: 168%;
    margin-left: 131%;
    margin-top: 12vh;
}
.ys3_ys{
    height: 29.5%;
    width: 37%;
    float: right;
    margin-top:0.8%;
}
.img3_ys{
    height: 100%;
    width: 100%;
    float: right;

}
.text3_ys{
    position: absolute;
    color: white;
    margin-left: 29.4%;
    float: left;
    margin-top: 6vh;
    height: 8%;
    width: 22%;
    -webkit-transform:scale(1);
    -webkit-transition-duration: 0.5s;
    font-size: 14px;
}
.line3_ys{
    background-image: url(../assets/images/ysblock/line1.png);
    background-size: 100% 100%;
    height: 44%;
    width: 168%;
    margin-left: 131.3%;
    margin-top: 6vh;
}
.ys4_ys{
    height: 39%;
    width: 49.5%;
    float: left;
    margin-top: 1%;
}
.img4_ys{
    height: 100%;
    width: 100%;
    float: left;
}
.text4_ys{
    position: absolute;
    color: white;
    margin-left: 61%;
    float: left;
    margin-top: 0vh;
    height: 8%;
    width: 22%;
    -webkit-transform:scale(1);
    -webkit-transition-duration: 0.5s;
    font-size: 14px;
}
.line4_ys{
    background-image: url(../assets/images/ysblock/line1.png);
    background-size: 100% 100%;
    height: 33%;
    width: 126%;
    margin-left: 225.5%;
    margin-top: 0vh;
}
.ys5_ys{
    height: 39%;
    width: 49.5%;
    float: right;
    margin-top: 1%;
}
.img5_ys{
    height: 100%;
    width: 100%;
    float: right;
}
.text5_ys{
    color: white;
    margin-left: 144.2%;
    float: left;
    margin-top: -10vh;
    height: 5vh;
    width: 90%;
    -webkit-transform:scale(1);
    -webkit-transition-duration: 0.5s;
    font-size: 14px;
    /* initial-letter: 1; */
    /* border: 1px solid red */
}
.line5_ys{
    background-image: url(../assets/images/ysblock/line1.png);
    background-size: 100% 100%;
    height: 33%;
    width: 127%;
    margin-left: 123.3%;
    margin-top: 9vh;
}
/* img{
    -webkit-transform:scale(1);
    -webkit-transition-duration: 0.5s;
    z-index: 1;
    position: relative;
} */
.img1_ys:hover,.img2_ys:hover,.img3_ys:hover.img4_ys:hover.img5_ys:hover{
    border: 2px solid white;
    -webkit-transform:scale(1.2);
	-webkit-box-shadow:0px 0px 30px #ccc;
    z-index: 2;
}
.ys1_ys:hover .text1_ys{
    color: rgb(51, 135, 214);;
    -webkit-transform:scale(1.1);
}
.ys1_ys:hover .img1_ys{
    border: 2px solid white;
    -webkit-transform:scale(1.2);
	-webkit-box-shadow:0px 0px 30px #ccc;
    z-index: 2;
}
.ys2_ys:hover .text2_ys{
    color: rgb(51, 135, 214);
    -webkit-transform:scale(1.1);
}
.ys2_ys:hover .img2_ys{
    border: 2px solid white;
    -webkit-transform:scale(1.2);
	-webkit-box-shadow:0px 0px 30px #ccc;
    z-index: 2;
}
.ys3_ys:hover .text3_ys{
    color: rgb(51, 135, 214);
    -webkit-transform:scale(1.1);
}
.ys3_ys:hover .img3_ys{
    border: 2px solid white;
    -webkit-transform:scale(1.2);
	-webkit-box-shadow:0px 0px 30px #ccc;
    z-index: 2;
}
.ys4_ys:hover .text4_ys{
    color: rgb(51, 135, 214);
    -webkit-transform:scale(1.1);
}
.ys4_ys:hover .img4_ys{
    border: 2px solid white;
    -webkit-transform:scale(1.2);
	-webkit-box-shadow:0px 0px 30px #ccc;
    z-index: 2;
}
.ys5_ys:hover .text5_ys{
    color: rgb(51, 135, 214);
    -webkit-transform:scale(1.1);
}
.ys5_ys:hover .img5_ys{
    border: 2px solid white;
    -webkit-transform:scale(1.2);
	-webkit-box-shadow:0px 0px 30px #ccc;
    z-index: 2;
}



.footer{
    width: 100%;
    height: 60px;
    background: rgb(187, 184, 184);
    text-align: center;
}
.back1_ys{
    background-image: url(../assets/images/ysblock/background1.png);
    background-size: cover;
    height: 110vh;
}
.titel1_ys{
    height: 8vh;
    width: 40%;
    background: white;
    margin-left: 30%;
    /* border:2px solid #ccc; */
    box-shadow: 2px 2px 1px  #ccc;
}
.code1_ys{
    height: 42vh;
    width:80%;
    margin-left: 10%;
    background-color: #ccc;
}
.code2_ys{
    height: 42vh;
    width:80%;
    margin-right: 10%;
    top: 10px;
    float: right;
    background: #ccc;
}
.img14_ys{
    float: left;
}
.img15_ys{
    float: right;
}
.color1_ys{
    width: 5%;
    height: 42vh;
    background: rgb(51, 135, 214);
    float: right;
}
.color2_ys{
    width: 5%;
    height: 42vh;
    background: rgb(51, 135, 214);
    float: left;
}
.text_14_ys{
    width: 45%;
    height: 42vh;
    float: left;
    padding: 2% 3%;

}
.text_15_ys{
    width: 45%;
    height: 42vh;
    padding: 2% 3%;
    float: right;
}






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
