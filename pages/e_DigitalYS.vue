<template>
    <div class="DigitalYS">
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
                                <a href="/DigitalYS">
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
                                    <nuxt-link to="/e_DigitalChina"><li>Digital China</li></nuxt-link>
                                    <nuxt-link to="/e_DigitalGX"><li>Digital Guangxi</li></nuxt-link>
                                    <nuxt-link to="/e_DigitalYL"><li>Digital Yulin</li></nuxt-link>
                                    <nuxt-link to="#"><li><div class="nav_5">Digital Yushi</div></li></nuxt-link>
                                    <nuxt-link to="/e_aboutMe"><li>About us</li></nuxt-link>
                                </ul>
                            </div>
                        </el-row>
                        </div>
                    </div>
                </div>
                <div class="YS">
                    <eysheader/>
                </div>
            </div>
        </div>
        <eysindex/>
        <el-backtop :bottom="100" style="color:transparent">
            <img src="../assets/images/111.png" alt="" style="color:transparent;" height="100%" width="100%">
        </el-backtop>
        <div class="footer5">Development team:Wuzheng Ningyufan Lushimei Yanxiaoqian Huangsisen</div>
    </div>
</template>

<script>
import eysheader from '../components/ys/e_ysheader.vue'
import eysindex from '../components/ys/e_ysindex.vue'
// import ysblockjs from '../components/ys/ys_block_js.vue'
// import ysblockscope from '../components/ys/ys_block_Scope.vue'
// import ysblockfzzj from '../components/ys/ys_block_fzzj.vue'
// import ysblockxq from '../components/ys/ys_block_xq.vue'
// import ysblockxw from '../components/ys/ys_block_xw.vue'
// import animated from 'animate.css' 
export default {
    components:{
        eysheader,
        eysindex
        // ysblockjs,
        // ysblockscope,
        // ysblockfzzj,
        // ysblockxq,
        // ysblockxw,
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
            {src:'js/particles.min.js'},
        ],
        link: [
            { rel: 'stylesheet', href: 'css/normalize.css' },
            // { rel: 'stylesheet', href: 'css/demo.css' },
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
.footer5{
    width: 100%;
    height: 60px;
    background: #2a53a9;
    text-align: center;
    font-size: 1.5vw;
    line-height: 4vw;
    font-family:cursive;
}



.back1_ys{
    background-image: url(../assets/images/ysblock/background1.png);
    background-size: cover;
    height: 110vh;
}
.titel1_ys{
    height: 8vh;
    width: 40%;
    font-size: 5vh;
    margin-left: 30%;
    /* border:2px solid #ccc; */
    color: rgb(51, 135, 214);
    text-align: center;
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
    color: black;

}
.text_15_ys{
    width: 45%;
    height: 42vh;
    padding: 2% 3%;
    float: right;
    color: black;
}

</style>
