<template>
    <div class="aboutMe">
        <div class="header_one">
            <div class="header " id="header" >
                <div class="logo">
                    <!-- <a href="#">
                        Digital <img src="../assets/images/logo.png" height="30vh" width="30vw" alt=""> China
                    </a> -->
                </div>
                <div class=" fixed-width clearfix" :class="{fixed: isFixed}">
                    <div class="header-title fl" style="text-align: center">
                        <div class="header_nav">
                        <el-row class="row_one">
                            <div class="ce_nav">
                                <a href="/aboutme">
                                    <i class="el-icon-star-off"><label>Chinese</label></i>
                                </a>
                                <a href="#">
                                    <i class="el-icon-star-on"><label>English</label></i>
                                </a>
                            </div>
                        </el-row>
                        <el-row class="row_tow">
                            <div class="nav">
                                <ul>
                                    <nuxt-link to="/english_index"><li>Home page</li></nuxt-link>
                                    <nuxt-link to="/e_digitalchina"><li>Digital China</li></nuxt-link>
                                    <nuxt-link to="/e_digitalgx"><li>Digital Guangxi</li></nuxt-link>
                                    <nuxt-link to="/e_digitalyl"><li>Digital Yulin</li></nuxt-link>
                                    <nuxt-link to="/e_digitalys"><li>Digital Yushi</li></nuxt-link>
                                    <nuxt-link to="#"><li><div class="nav_6">About us</div></li></nuxt-link>
                                </ul>
                            </div>
                        </el-row>
                        </div>
                    </div>
                </div>
                <div class="ME">
                    <header class="hero">
                        <div class="hero-center">
                            <h2 style="font-family:STXingkai;color: rgb(48, 189, 245);font-size:3vh;" aos="fade-up" aos-easing="ease" aos-delay="100">About Web Pages</h2>
                            <br>
                            <h2 style="font-family:STXingkai;color: rgb(48, 189, 245);font-size:3vh;" aos="fade-up" aos-easing="ease" aos-delay="250">This web page was completed one day in 2019. The design of the web page is hierarchical. The content of the web page is loaded by rolling aos, with the animation effects of native js, fade in and fade out</h2>
                            <br>
                            <h2 style="font-family:STXingkai;color: rgb(48, 189, 245);font-size:3vh;" aos="fade-up" aos-easing="ease" aos-delay="400">Make the browser more comfortable and clear to browse the content of the web page, and use js and other frameworks to make the coding more concise and more efficient.</h2>
                            <br>
                            <h2 style="font-family:STXingkai;color: rgb(48, 189, 245);font-size:3vh;" aos="fade-up" aos-easing="ease" aos-delay="550">Our team is dedicated to creating more perfect and excellent web pages and striving for self-improvement all the time</h2>
                            <br>
                            <h2 style="font-family:STXingkai;color: rgb(48, 189, 245);font-size:3vh;" aos="fade-up" aos-easing="ease" aos-delay="700">Youth has no rest station, only the image of hard struggle</h2>
                        </div>
                        <span class="hero__scroll" aos="fade-up" aos-easing="ease" aos-delay="850" @click="videoon()">
                            <h4 style="color: rgb(48, 189, 245);font-family:STXingkai;font-size:2vh;">Click drop-down</h4>
                            <i class="chevron bottom"></i>
                            <!-- {{text}}{{isFixed}} -->
                        </span>
                    </header>
                </div>
            </div>
        </div>



        <div id="aboutbody">
            <div class="video_me" v-show="video">
                <video id="video1" src="@/assets/video/team.mp4" preload="auto" style="dispaly:inline"
                 playsinline='true' webkit-playsinline='true' width="100%" height="100%" >
                </video>
            </div>


            <div class="zoomIn">
                <div class="main-body">
                    <div>
                        <div class="cklice1" >
                            <div class="cklice2 left"><img class="katong_about" src='@/assets/images/ysblock/kt1.jpg' height="100%" width="100%"></div>
                            <div class="cklice3">
                                <br><br>
                                <div class="nameabout">Wuzheng</div>
                                <div class="text_about">College of Computer Science and Engineering</div>
                                <!-- <div class="text_about">Computer Science and Technology</div> -->
                                <div class="text_about">Responsible for code editing, page design and overall planning of web pages</div>
                            </div>
                        </div>
                        <div class="cklice4"></div>
                    </div>
                </div>
                <div class="main-body">
                    <div>
                        <div class="cklice5 " >
                            <div class="cklice6 left"><img class="katong_about" src='@/assets/images/ysblock/kt3.jpg' height="100%" width="100%"></div>
                            <div class="cklice7">
                                <br><br>
                                <div class="nameabout">Ningyufan</div>
                                <div class="text_about">College of Computer Science and Engineering</div>
                                <!-- <div class="text_about">Computer Science and Technology</div> -->
                                <div class="text_about">Responsible for Code Editing of Web Pages, Searching for Material and Creativity</div>
                            </div>
                        </div>
                        <div class="cklice8"></div>
                    </div>
                </div>
                <div class="main-body">
                    <div>
                        <div class="cklice9 " >
                            <div class="cklice10 left"><img class="katong_about" src='@/assets/images/ysblock/kt2.jpg' height="100%" width="100%"></div>
                            <div class="cklice11">
                                <br><br>
                                <div class="nameabout">Lushimei</div>
                                <div class="text_about">College of Computer Science and Engineering</div>
                                <!-- <div class="text_about">Computer Science and Technology</div> -->
                                <div class="text_about">Be responsible for the code editing of web pages and assist in page design</div>
                            </div>
                        </div>
                        <div class="cklice12"></div>
                    </div>
                </div>
                <div class="main-body">
                    <div>
                        <div class="cklice13 " >
                            <div class="cklice14 left"><img class="katong_about" src='@/assets/images/ysblock/kt4.jpg' height="100%" width="100%"></div>
                            <div class="cklice15">
                                <br><br>
                                <div class="nameabout">Yanxiaoqian</div>
                                <div class="text_about">College of Computer Science and Engineering</div>
                                <!-- <div class="text_about">Computer Science and Technology</div> -->
                                <div class="text_about">Responsible for page code editing, material sorting, page design</div>
                            </div>
                        </div>
                        <div class="cklice16"></div>
                    </div>
                </div>
                <div class="main-body">
                    <div>
                        <div class="cklice17 " >
                            <div class="cklice18 left"><img class="katong_about" src='@/assets/images/ysblock/kt5.jpg' height="100%" width="100%"></div>
                            <div class="cklice19">
                                <br><br>
                                <div class="nameabout">Huangsisen</div>
                                <div class="text_about">College of Computer Science and Engineering</div>
                                <!-- <div class="text_about">Computer Science and Technology</div> -->
                                <div class="text_about">Responsible for page code editing, material sorting, page design</div>
                            </div>
                        </div>
                        <div class="cklice20"></div>
                    </div>
                </div>
            </div>
        </div>

        <el-backtop :bottom="100" style="color:transparent">
            <img src="../assets/images/111.png" alt="" style="color:transparent;" height="90%" width="90%">
        </el-backtop>
        <div class="footer6">Development team:Wuzheng Ningyufan Lushimei Yanxiaoqian Huangsisen</div>
        
    </div>
</template>

<script>
// import aboutbody from '../components/aboutbody.vue'
// if (process.browser) { // 在这里根据环境引入wow.js
//     var {WOW} = require('wowjs')
//     }
export default {
    components:{
        // aboutbody,
    },
    data () {
        return {
            isFixed: 0,
            text:1,
            video:false,
        }
    },
        head:{
        script:[
            {src:'js/jquery.1.7.1.min.js'},
            {src:'js/aos.js'},
            {src:'js/jquery.min.js'},
            {src:'js/particles.min.js'},
        ],
        link: [
            { rel: 'stylesheet', href: 'css/normalize.css' },
            // { rel: 'stylesheet', href: 'css/demo.css' },
            { rel: 'stylesheet', href: 'js/aos.css' },
            { rel: 'stylesheet', href: 'css/styles.css' },
            // { rel: 'stylesheet', href: 'css/style_about.css' },
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
        videoon(){
            this.video=true;
            var myVideo=document.getElementById("video1");
            myVideo.play();
            
            // this.rrr=true
        },
        // start2(){
        //     var myVideo=document.getElementById("video1");
        //     // this.isFixed = 0;
        //     // this.text=2;
        //     let top = pageYOffset || document.documentElement.scrollTop || document.body.scrollTop;
        //     if(this.text = 1){
        //         myVideo.play();         
        //     }else if(top < 200){
        //         myVideo.pause();
        //     }
        // },
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
            });

        },
        nav(idx){
            this.nav_lock = idx
        }
    },
    mounted() {
        this.start();
        // this.start2();
        // this.handleAnimate();
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
            addEventListener('scroll', this.handleAnimate,{once:true});
            addEventListener('scroll', this.start2,{once:true});
            // addEventListener('scroll', this.start);
            

        })
        
    },
    destroyed() {
        removeEventListener('scroll', this.handleScroll);//避免影响其他页面
        removeEventListener('scroll', this.handleAnimate);
        removeEventListener('scroll', this.start2);      
    },

}
</script>

<style>
@import "@/assets/css/index/page_index.css";
.aboutMe {
    width: 100%;
    /* position:absolute;
    z-index: 1; */
    /* overflow:inherit; */
}
.style1{
    display: none;
}

/* .style2{
    display: block;
} */

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
.footer6{
    width: 100%;
    height: 60px;
    background: #2a53a9;
    text-align: center;
    font-size: 1.5vw;
    line-height: 4vw;
    font-family:STXingkai;
    color: white;
}
.katong_about{
    border-radius: 16vh;
    border: 1.5vh solid rgba(255, 255, 255, 0.6);
    filter:brightness(70%);
}

.cklice1{
    position: absolute;
    width: 32vh;
    height: 32vh;
    border-radius: 16vh;
    float: left;
    margin-left: 85vh;
    min-width: 20vh;
    min-height: 20vh;
    margin-top: 0vh;
    }
.cklice2{
    width: 32vh;
    height: 32vh;
    background-color: rgb(151, 150, 155);
    border-radius: 16vh;
    float: left;
    transform-origin:left;
    transform:scale(1);
    transition: all 0.2s ease-in;
    /* border: 1.5vh solid rgba(255, 255, 255, 0.2); */
    position: relative;
    z-index: 3;  
}
.cklice3{
    position: relative;
    width: 32vh;
    height: 32vh;
    background-color: rgb(197, 194, 194);
    border-radius: 16vh;
    margin-left: 40vh;
    left: -10vh;
    transition: all 0.2s ease-in;
    transition-timing-function: linear;
    opacity: 0;
    z-index: 1;
    padding: 0vh 1.5vh;
    /* text-align: center; */
    /* transition: margin-left 0.3s ease-in; */
}
.cklice4{
    position: relative;
    width: 32vh;
    height: 32vh;
    background-color: rgb(197, 194, 194);
    border-radius: 16vh;
    margin-left: 125vh;
    left: -10vh;
    transition: all 0.2s ease-in;
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

.cklice5{
    position: absolute;
    width: 32vh;
    height: 32vh;
    border-radius: 16vh;
    float: left;
    margin-left: 135vh;
    min-width: 20vh;
    min-height: 20vh;
    margin-top: 0vh;
    }
.cklice6{
    width: 32vh;
    height: 32vh;
    background-color: rgb(151, 150, 155);
    border-radius: 16vh;
    float: left;
    transform-origin:left;
    transform:scale(1);
    transition: all 0.2s ease-in;
    /* border: 1.5vh solid rgba(255, 255, 255, 0.2); */
    position: relative;
    z-index: 3;
    
}

.cklice7{
    position: relative;
    width: 32vh;
    height: 32vh;
    background-color: rgb(197, 194, 194);
    border-radius: 16vh;
    margin-left: 40vh;
    left: -10vh;
    transition: all 0.2s ease-in;
    transition-timing-function: linear;
    opacity: 0;
    z-index: 1;
    padding: 0vh 1.5vh;
}
.cklice8{
    position: relative;
    width: 32vh;
    height: 32vh;
    background-color: rgb(197, 194, 194);
    border-radius: 16vh;
    margin-left: 175vh;
    left: -10vh;
    transition: all 0.2s ease-in;
    transition-timing-function: linear;
    opacity: 0;
    margin-top: 35vh;
    z-index: 3;
}
.cklice5:hover .cklice6{
    transform:scale(0.6);
    margin-left: -10vh;
}
.cklice5:hover .cklice7{
    margin-left: 10vh;
    opacity: 1;
}

.cklice9{
    position: absolute;
    width: 32vh;
    height: 32vh;
    border-radius: 16vh;
    float: left;
    margin-left: 35vh;
    min-width: 20vh;
    min-height: 20vh;
    margin-top: 0vh;
    }
.cklice10{
    width: 32vh;
    height: 32vh;
    background-color: rgb(151, 150, 155);
    border-radius: 16vh;
    float: left;
    transform-origin:left;
    transform:scale(1);
    transition: all 0.2s ease-in;
    /* border: 1.5vh solid rgba(255, 255, 255, 0.2); */
    position: relative;
    z-index: 3;
}

.cklice11{
    position: relative;
    width: 32vh;
    height: 32vh;
    background-color: rgb(197, 194, 194);
    border-radius: 16vh;
    margin-left: 40vh;
    left: -10vh;
    transition: all 0.2s ease-in;
    transition-timing-function: linear;
    opacity: 0;
    z-index: 1;
    padding: 0vh 1.5vh;
}
.cklice12{
    position: relative;
    width: 32vh;
    height: 32vh;
    background-color: rgb(197, 194, 194);
    border-radius: 16vh;
    margin-left: 75vh;
    left: -10vh;
    transition: all 0.2s ease-in;
    transition-timing-function: linear;
    opacity: 0;
    margin-top: 35vh;
    z-index: 3;
}
.cklice9:hover .cklice10{
    transform:scale(0.6);
    margin-left: -10vh;
}
.cklice9:hover .cklice11{
    margin-left: 10vh;
    opacity: 1;
}

.cklice13{
    position: absolute;
    width: 32vh;
    height: 32vh;
    border-radius: 16vh;
    float: left;
    margin-left: 55vh;
    min-width: 20vh;
    min-height: 20vh;
    margin-top: 0vh;
}
.cklice14{
    width: 32vh;
    height: 32vh;
    background-color: rgb(151, 150, 155);
    border-radius: 16vh;
    float: left;
    transform-origin:left;
    transform:scale(1);
    transition: all 0.2s ease-in;
    /* border: 1.5vh solid rgba(255, 255, 255, 0.2); */
    position: relative;
    z-index: 3;
    
}
.cklice15{
    position: relative;
    width: 32vh;
    height: 32vh;
    background-color: rgb(197, 194, 194);
    border-radius: 16vh;
    margin-left: 40vh;
    left: -10vh;
    transition: all 0.2s ease-in;
    transition-timing-function: linear;
    opacity: 0;
    z-index: 1;
    padding: 0vh 1.5vh;
}
.cklice16{
    position: relative;
    width: 32vh;
    height: 32vh;
    background-color: rgb(197, 194, 194);
    border-radius: 16vh;
    margin-left: 95vh;
    left: -10vh;
    transition: all 0.2s ease-in;
    transition-timing-function: linear;
    opacity: 0;
    margin-top: 78vh;
    z-index: 3;
}
.cklice13:hover .cklice14{
    transform:scale(0.6);
    margin-left: -10vh;
}
.cklice13:hover .cklice15{
    margin-left: 10vh;
    opacity: 1;
}

.cklice17{
    position: absolute;
    width: 32vh;
    height: 32vh;
    border-radius: 16vh;
    float: left;
    margin-left: 115vh;
    min-width: 20vh;
    min-height: 20vh;
    margin-top: 0vh;
}
.cklice18{
    width: 32vh;
    height: 32vh;
    background-color: rgb(151, 150, 155);
    border-radius: 16vh;
    /* margin-left: 80%; */
    float: left;
    transform-origin:left;
    transform:scale(1);
    transition: all 0.2s ease-in;
    /* border: 1.5vh solid rgba(255, 255, 255, 0.2); */
    position: relative;
    z-index: 3;
    
}
.cklice19{
    position: relative;
    width: 32vh;
    height: 32vh;
    background-color: rgb(197, 194, 194);
    border-radius: 16vh;
    margin-left: 40vh;
    left: -10vh;
    transition: all 0.2s ease-in;
    transition-timing-function: linear;
    opacity: 0;
    z-index: 1;
    padding: 0vh 1.5vh;
}
.cklice20{
    position: relative;
    width: 32vh;
    height: 32vh;
    background-color: rgb(197, 194, 194);
    border-radius: 16vh;
    margin-left: 155vh;
    left: -10vh;
    transition: all 0.2s ease-in;
    transition-timing-function: linear;
    opacity: 0;
    margin-top: 78vh;
    z-index: 3;
}
.cklice17:hover .cklice18{
    transform:scale(0.6);
    margin-left: -10vh;
}
.cklice17:hover .cklice19{
    margin-left: 10vh;
    opacity: 1;
}







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
.zoomIn{
    animation: zoomIn 3s ease-in;
    animation-delay:12s; 
}
.main-body{
    position:absolute;
    top:100vh;
    width:100%;
    height:100%;
}
.nameabout{
    font-family: 华文行楷;
    font-size: 3vh;
}
.text_about{
    font-size: 2.5vh;
    line-height: 2.75vh;
    font-family: 华文行楷;
}
</style>