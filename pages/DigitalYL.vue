<template>
    <div class="DigitalYL">
        <div class="header_one">
            <div class="header " id="header" >
                <div class="logo">
                    <a href="#">
                        <!-- Digital <img src="../assets/images/logo.png" height="30vh" width="30vw" alt=""> China -->
                    </a>
                </div>
                <div class=" fixed-width clearfix" :class="{fixed: isFixed}">
                    <div class="header-title fl" style="text-align: center">
                        <div class="header_nav">
                        <el-row class="row_one">
                            <div class="ce_nav">
                                <a href="#">
                                        <i class="el-icon-star-on"><label>中</label></i>
                                    </a>
                                    <a href="/e_DigitalYL">
                                        <i class="el-icon-star-off"><label>英</label></i>
                                    </a>
                            </div>
                        </el-row>
                        <el-row class="row_tow">
                            <div class="nav">
                                <ul>
                                    <nuxt-link to="/chinese_index"><li>首页</li></nuxt-link>
                                    <nuxt-link to="/Digital_China"><li>数字中国</li></nuxt-link>
                                    <nuxt-link to="/DigitalGX"><li>数字广西</li></nuxt-link>
                                    <nuxt-link to="#"><li><div class="nav_4">数字玉林</div></li></nuxt-link>
                                    <nuxt-link to="/DigitalYS"><li>数字玉师</li></nuxt-link>
                                    <nuxt-link to="/aboutMe"><li>关于我们</li></nuxt-link>
                                </ul>
                            </div>
                        </el-row>
                        </div>
                    </div>
                </div>
                <div class="YL">
                    <ylHeader />
                </div>
            </div>
        </div>
        <ylBody />
        <div class="footer">开发团队：吴证 宁玉帆 陆石媚 严晓倩 黄思森</div>
    </div>


</template>


<script>
    import ylHeader from '../components/yulin/ylheader'
    import ylBody from '../components/yulin/ylbody'
export default {
    components:{
        ylHeader,
        ylBody
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
.DigitalYL {
    width: 100%;
}
.nav_4{
    background-image: url('../assets/images/bg_xuanzhong.png');
    background-size: 100% 7.5vh ;
}
.nav:hover .nav_4{
    background: none;
}
.YL{
    color: white;
    width: 80%;
    margin-left: 10%
}
.footer{
    width: 100%;
    height: 60px;
    background: #2a53a9;
    text-align: center;
    font-size: 1.5vw;
    line-height: 4vw;
    font-family:STXingkai;
    color: white;
    /* margin-bottom: 4vh; */
}
</style>