<template>
<div class="DigitalChina">
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
                                        <nuxt-link to="#"><li><div class="nav_2">数字中国</div></li></nuxt-link>
                                        <nuxt-link to="/DigitalGX"><li>数字广西</li></nuxt-link>
                                        <nuxt-link to="/DigitalYL"><li>数字玉林</li></nuxt-link>
                                        <nuxt-link to="/DigitalYS"><li>数字玉师</li></nuxt-link>
                                        <nuxt-link to="/aboutMe"><li>关于我们</li></nuxt-link>
                                    </ul>
                                </div>
                            </el-row>
                        </div>
                    </div>
                </div>
                <div class="china">
                    <DigitalIndex/>
                </div>
            </div>
        </div>
            <div class="digital_bg">
            <div class="digital_header">
                <div class="digital_bk1">
                    <DigitalVideo/>
                </div>
            </div>
            <div class="digital_yuan">
            <div class="digital_yuan1"></div>
            <div class="digital_yuan2"></div>
            </div>
            <DigitalFooter/>
        </div>
        <div class="footer">footer</div>
    </div>
</template>

<script>
import DigitalIndex from '../components/dchina/DigitalChina_index'
import DigitalVideo from '../components/dchina/DigitalChina_video'
import DigitalFooter from '../components/dchina/Digital_footer'
export default {
    head:{
        script:[
            {src:'js/jquery.1.7.1.min.js'},
            {src:'js/aos.js'},
        ],
        link: [
            { rel: 'stylesheet', href: 'css/normalize.css' },
            // { rel: 'stylesheet', href: 'css/demo.css' },
            { rel: 'stylesheet', href: 'js/aos.css' },
            { rel: 'stylesheet', href: 'css/styles.css' }
        ]
    },
    components:{
            DigitalIndex,DigitalVideo,DigitalFooter
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
    AOS.init({
        easing: 'ease-out-back',
        duration: 1000
    });
    removeEventListener('scroll', this.handleScroll);//避免影响其他页面
    removeEventListener('scroll', this.handleAnimate);
    },

}
</script>

<style>
@import "@/assets/css/index/page_index.css";
@import "@/assets/css/digital_china.css";
.DigitalChina{
    width: 100%;
}
.nav_2{
    background-image: url('../assets/images/bg_xuanzhong.png');
    background-size: 100% 7.5vh ;
}
.nav:hover .nav_2{
    background: none;
}
.china{
    color: white;
    width: 80%;
    height: 60%;
    margin-left: 10%
}
.footer{
    width: 100%;
    height: 60px;
    background: rgb(187, 184, 184);
    text-align: center;
}



.digital_yuan{
    position: absolute;
    width: 100%;
    height: 40%;
    top: 100vh;
}

.digital_yuan1{
    position: relative;
    background-image: url('../assets/images/dchina/yuan.png');
    width: 10%;
    height: 30%;
    float: left;
    background-size: 100% 100%;
    background-position: center center;
    box-shadow:#1E90FF 0 0 30px 5px;
    border-radius: 50%;
    transform: rotate(0deg);
    animation: zhuandong1 5s linear infinite;
}
@keyframes zhuandong1{
        from{
        transform: rotate(0deg);
        }
        to{
        transform: rotate(-360deg);
        }
        }

.digital_yuan2{
    position: relative;
    background-image: url('../assets/images/dchina/yuan.png');
    width: 10%;
    height: 30%;
    float: right;
    margin-right: 2vh;
    margin-top: 10vh;
    background-size: 100% 100%;
    background-position: center center;
    box-shadow:#1E90FF 0 0 30px 5px;
    border-radius: 50%;
    transform: rotate(0deg);
    animation: zhuandong2 5s linear infinite;
}
@keyframes zhuandong2{
        from{
        transform: rotate(0deg);
        }
        to{
        transform: rotate(360deg);
        }
        }

</style>