<template>
    <div class="aboutMe">
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
                                    <nuxt-link to="/DigitalYS"><li>数字玉师</li></nuxt-link>
                                    <nuxt-link to="/aboutMe"><li><div class="nav_6">关于我们</div></li></nuxt-link>
                                </ul>
                            </div>
                        </el-row>
                        </div>
                    </div>
                </div>
                <div class="ME">
                    <header class="hero">
                        <div class="hero-center">
                            <h1 style="font-family:Microsoft YaHei">页面滚动元素动画插件-aos.js</h1>
                            
                            <h2 class="hero__text" aos="fade-up" aos-easing="ease" aos-delay="400">Animate On Scroll <span>Library</span></h2>
                        </div>
                        <span class="hero__scroll" aos="fade-up" aos-easing="ease" aos-delay="800">
                            点击下拉 <br>
                            <i class="chevron bottom"></i>
                        </span>
                    </header>
                </div>
            </div>
        </div>

        <div id="aboutbody" >
            <div class="video_me">
                <video id="video1" src="@/assets/video/team.mp4" preload="auto" style="dispaly:inline"
                 playsinline='true' webkit-playsinline='true' width="100%" height="100%" >
                </video>
            </div>

            <div class="main-body">
                <div class="cklice1">
                    <div class="cklice2 left"></div>
                    <div class="cklice3">sss</div>
                </div>
                <div class="cklice4">sss</div>
                

                
            </div>




        </div>
        <!-- <aboutbody/> -->



        
        <div class="footer">footer</div>
    </div>
</template>

<script>
import aboutbody from '../components/aboutbody.vue'
// if (process.browser) { // 在这里根据环境引入wow.js
//     var {WOW} = require('wowjs')
//     }
export default {
    components:{
        aboutbody,
    },
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
            // { rel: 'stylesheet', href: 'css/demo.css' },
            { rel: 'stylesheet', href: 'js/aos.css' },
            { rel: 'stylesheet', href: 'css/styles.css' },
            // { rel: 'stylesheet', href: 'styles/yl_main.css' },
            // { rel: 'stylesheet', href: 'css/default.css' },
            // { rel: 'stylesheet', href: 'css/normalize.css' },
        ]
    },
    methods: {
        start(){
            $('.hero__scroll').on('click', function(e) {
			$('html, body').animate({
				scrollTop: $(window).height()
			}, 1200);
		    });
        },
        start2(){

 
            var myVideo=document.getElementById("video1");
            if(this.isFixed = 1){
                myVideo.play();
            }

        },
        handleScroll() {
            var myVideo=document.getElementById("video1");
            let top = pageYOffset || document.documentElement.scrollTop || document.body.scrollTop;
            if(top > 250){
                this.isFixed = 1;

            }
            else if(top < 200){
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
        this.start();
        
        // if (process.browser) {  // 在页面mounted生命周期里面 根据环境实例化WOW
        //     new WOW({
        //         live: true, 
        //         offset: 0
        //     }).init()
        // };
        AOS.init({
            easing: 'ease-out-back',
            duration: 1000
        });
        this.$nextTick(() => {
            
            this.handleAnimate()//初始化第一次加载时在视口内就执行动画
            addEventListener('scroll', this.handleScroll);
            addEventListener('scroll', this.handleAnimate);
            addEventListener('scroll', this.start2,{once:true});

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
.aboutMe {
    width: 100%;
}
.nav_6{
    background-image: url('../assets/images/bg_xuanzhong.png');
    background-size: 100% 7.5vh ;
}
.nav:hover .nav_6{
    background: none;
}
.ME{
    color: white;
    width: 80%;
    margin-left: 10%
}
.footer{
    width: 100%;
    height: 60px;
    background: rgb(187, 184, 184);
    text-align: center;
}
/* .video_me{
    height: 100%;
    width: 100%;
} */
.cklice1{
    position: absolute;
    width: 30vh;
    height: 30vh;
    background-color: rgb(144, 33, 33);
    border-radius: 100px;
    float: left;
    margin-left: 85vh;
    min-width: 20vh;
    min-height: 20vh;
    margin-top: 7vh;
    }
.cklice2{
    width: 30vh;
    height: 30vh;
    background-color: rgb(151, 150, 155);
    border-radius: 15vh;
    /* margin-left: 80%; */
    float: left;
    transform-origin:left;
    transform:scale(1);
    transition: all 0.3s ease-in;
    border: 1.5vh solid rgba(255, 255, 255, 0.2);
    position: relative;
    z-index: 3;
    
}

.cklice3{
    position: relative;
    width: 30vh;
    height: 30vh;
    background-color: rgb(197, 194, 194);
    border-radius: 15vh;
    margin-left: 40vh;
    left: -10vh;
    transition: all 0.3s ease-in;
    transition-timing-function: linear;
    opacity: 0;
    z-index: 1;
    /* transition: margin-left 0.3s ease-in; */
}
.cklice4{
    position: relative;
    width: 30vh;
    height: 30vh;
    background-color: rgb(197, 194, 194);
    border-radius: 15vh;
    margin-left: 125vh;
    left: -10vh;
    transition: all 0.3s ease-in;
    transition-timing-function: linear;
    opacity: 0;
    margin-top: 7vh;
    z-index: 3;
    /* transition: margin-left 0.3s ease-in; */
}
.cklice1:hover .cklice2{
    transform:scale(0.6);
    margin-left: -10vh;

}

.cklice1:hover .cklice3{
    margin-left: 10vh;
    opacity: 1;
    

}
.cklice1:hover 










#aboutbody{
    background-color: white;
    height: 100%;
    overflow:hidden;
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
.main-body{
    position:absolute;
    top:100vh;
    width:100%;
    height:100%;
}
</style>