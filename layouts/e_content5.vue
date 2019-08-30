<template>
    <div class="Digital_ct">       	
        <div class="ct_mbg" id="ct_mbg"> 
                <div class=" fixed-width clearfix" :class="{fixed: isFixed}">
                    <div class="header-title fl" style="text-align: center">
                        <div class="header_nav1">
                            <div class="row1_one">
                                <div class="ce_nav1">
                                    <a href="#">
                                        <i class="el-icon-star-on">Chinese</i>
                                    </a>
                                    <a href="#">
                                        <i class="el-icon-star-off">English</i>
                                    </a>
                                </div>
                            </div>
                            <div class="row1_two">
                                <div class="nav">
                                    <ul>
                                        <nuxt-link to="/english_index"><li>Home page</li></nuxt-link>
                                        <nuxt-link to="/e_DigitalChina"><li>Digital China</li></nuxt-link>
                                        <nuxt-link to="/e_DigitalGX"><li>Digital Guangxi</li></nuxt-link>
                                        <nuxt-link to="/e_DigitalYL"><li>Digital Yulin</li></nuxt-link>
                                        <nuxt-link to="/e_DigitalYS"><li><div class="nav_5">Digital Yushi</div></li></nuxt-link>
                                        <nuxt-link to="/e_aboutMe"><li>About us</li></nuxt-link>
                                    </ul>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="ct_border">
                    <center>
                    <div class="ct_bg">
                            <div class="ct_main">
                                <div class="ct_logo" aos="zoom-in">
                                    <span style="color:#00F5FF;">
                                       <img src="../assets/images/logo.png" height="50vh" width="50vw" alt=""> 
                                       DigitalChina
                                    </span>
                                </div>
                                <div class="fg_border"></div>
                                <div class="content">
                                    <nuxt />
                                </div>
                                
                            </div>
                    </div>
                    </center>
                </div>
                <canvas></canvas>
        </div>
        <div class="footer">footer</div>
        <script src='js/ct-dh.js'></script>
    </div>
</template>
<script>
export default {
    head:{
        script:[
            {src:'js/jquery.1.7.1.min.js'},
            {src:'js/aos.js'},
        ],
        link: [
            { rel: 'stylesheet', href: 'css/normalize.css' },
            { rel: 'stylesheet', href: 'js/aos.css' },
            { rel: 'stylesheet', href: 'css/styles.css' },
        ]
    },
    data () {
    return {
        isFixed: 0,
    }
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
        },
        
    }, 
    mounted(){
    AOS.init({
        easing: 'ease-out-back',
        duration: 1000,
    });
    // this.$nextTick(() => {
    //     this.handleAnimate()//初始化第一次加载时在视口内就执行动画
    //     addEventListener('scroll', this.handleScroll);
    //     addEventListener('scroll', this.handleAnimate);

    // })
    },
    // destroyed() {
    // removeEventListener('scroll', this.handleScroll);//避免影响其他页面
    // removeEventListener('scroll', this.handleAnimate);
    // },
}
</script>

<style>
@import "@/assets/css/index/page_index.css";
.J_dotLine{
	height:20vh;
	width:100vw;
}

.Digital_ct{
    width: 100%;
}
.ct_mbg{
    background-image: url('../assets/images/dchina/ct_bg2.png');
    width: 100vw;
    height: 200vh;
    background-size: 100% 100%; 
    position: relative;
    z-index: 1;
}

.header_nav1{
  position: absolute;
  height:15vh;
  width: 100vw;
  margin: 0 auto;
}

.row1_two{
    padding-top: 6vh;
}

.ce_nav1 {
 height: 16vh;
 float: right;
 padding-right: 8vh;
 padding-top: 8vh;
 font-size: 2.5vh;
 
}

.nav_5{
    background-image: url('../assets/images/bg_xuanzhong.png');
    background-size: 100% 7.5vh ;
}
.nav:hover .nav_5{
    background: none;
}
.footer{
    width: 100%;
    height: 60px;
    background: rgb(187, 184, 184);
    text-align: center;
}


.ct_border{
    height: 160vh;
    width: 60%;
    margin: 0 auto;
    z-index: 2;
    position: absolute;
    top:20vh;
    left: 20vw;
    border:2vh solid rgba(255, 255, 255, 0.5);
}

.ct_bg{
    height: 150vh;
    width: 50vw;
    margin:0 auto;
    background-color:rgba(255, 255, 255, 0.5);
    z-index: 3;
    top:3vh;
    position: relative;
}

.ct_logo {
    position: absolute;
    height: 16.5vh;
    float: left;
    padding-left: 2vh;
    padding-top: 2vh;
    font-size: 4vh;
    z-index:4;
}

.fg_border{
    width: 100%;
    margin: 0 auto;
    z-index: 2;
    position: absolute;
    top: 10vh;
    border:1vh solid rgba(255, 255, 255, 0.5);
}
.content {
    position: absolute;
    top: 15vh;
    left: 5%;
    width: 90%;
    height:85%;  
}
</style>