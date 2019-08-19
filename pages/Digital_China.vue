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
                <div class="china"><DigitalIndex/></div>
            </div>
        </div>
        <div class="digital_bg">
            <div class="digital_header">
                <div class="digital_bk1">
                    <DigitalVideo/>
                </div>
            </div>
            <div class="digital_footer">
                <div class="digital_bk2">
                    <a href="#" style="color:white">
                    <div class="footer_left">
                        <div class="left_ct">
                            <h3>南京打造数字经济名城</h3>
                            <p>在前不久落幕的第十五届中国（南京）国际软件产品和信息服务交易博览会
                                （以下简称软博会）上，来自全球30多个国家和地区的1200多家企业齐聚
                                古都南京，共同展望“数字经济”下的“智慧未来”，共签约项目80余项，总
                                投资额超过340亿元。</p>
                        </div>
                        <div class="left_img">
                            <p>见证了南京软件产业从起步到腾飞的南京软博会，
                                十四年来，其规模由小到大，参展企业越来越多，由着重服务外包发展成引
                                领新经济前沿，现已成为南京“新经济”发展的风向标。软博会在留下累累硕
                                果的同时，也给全体南京市民留下深深思索：即将迈过5000亿元规模门槛的
                                南京软件业，如何在新一轮发展大潮中抢抓机遇，破解增长速度不够快、龙
                                头企业不够多的难题？同时，如何借力软件产业，进一步迈向“数字经济名城”？（来源：学习强国）</p>
                            <div class="nanjing_img"></div>
                        </div>
                    </div>
                    </a>
                </div>
                <div class="digital_bk3"> 
                    <a href="#" style="color:white">
                    <div class="footer_right">
                        <div class="right_ct">
                            <h3>数字经济将重塑中国制造</h3>
                            <p>吸尘器车间经智能化改造后实现“关灯作业”，传统钣金制造在数字化平台辅助
                                下，生产效率提高三成；无人驾驶汽车依托物联网传感技术，完成了变道、超
                                车、减速等系列操作……记者近期在我国东部城市采访发现，数字经济的异军突
                                起，正深度重构中国制造。</p>
                        </div>
                        <div class="right_img">
                            <p>在新一轮科技革命和产业变革蓄势待发时期，我国数字经济规模持续扩大。根据
                                中国信息通信产业研究院发布的《中国数字经济发展与就业白皮书（2019年）》
                                显示，2018年中国数字经济规模达到31.3万亿元，占GDP比重为34.8%。（来源：学习强国）</p>
                            <div class="zhizao_img"></div>
                        </div>
                    </div>
                    </a>
                </div>   
            </div>
        </div>
        <div class="footer">footer</div>
    </div>
</template>

<script>
import DigitalIndex from '../components/dchina/digital_index'
import DigitalVideo from '../components/dchina/digital_video'
import Video from 'video.js'
export default {
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
    components:{
            DigitalIndex,DigitalVideo,Video
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
</style>