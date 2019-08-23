<template>
    <div class="Digital_JZ">
        <div class="JZ_bg"></div>
        <div class="JZ_ct">
            <center>
            <h2>数字经济影响城市未来竞争格局</h2></center><br/>
            <p>古老街区遇上数字中国，将发生怎样的蝶变？作为第二届数字中国建设峰会预热活动，“有福之州·对话未来”
                5月5日在福州三坊七巷举行，各界人士齐聚一堂，畅想未来。</p>
            <p>城市让生活更美好，数字经济让城市更美好。一方面，数字经济有助于城市优化资源配置、创新增
                长方式、培育发展新动能；另一方面，大数据、云计算、物联网等信息技术的应用，有助于打破
                “信息孤岛”，提升政府决策科学化、城市管理精细化以及公共服务便利化水平，提升人民群众获得
                感、幸福感和安全感。
            </p>
            <p>以福州为例，2018年福州数字经济规模突破2800亿元，占地区生产总值的36%。在民生领域，国家健
                康医疗大数据（福州）服务平台覆盖人群达711万，汇聚数据超200亿条，通过“大数据+医疗”，提升
                了基层诊疗水平，有效解决了医疗资源分布不均的问题，实现了“数据多跑路，群众少跑腿”，成为医
                疗惠民的有效支撑。
            </p>
            <p>国家发展改革委近期公布的《2019年新型城镇化建设重点任务》明确提出，要优化提升新型智慧城市建
                设评价工作，指导地级以上城市整合建成数字化城市管理平台，增强城市管理综合统筹能力，提高城市
                科学化、精细化、智能化管理水平。</p>
            <p>数字城市建设为未来城市竞争格局提供了新的观察视角。随着数字经济发展，西部城市也可以与东部城市
            站在同一起跑线上。这就要求各地抓住契机，跨越数字鸿沟，通过发展数字经济，加快产业升级步伐。</p>
            <p>进一步来说，数字城市由谁建？怎么建？数字城市建设需求多样、技术复杂，这需要包括政府、企业、
            高校、科研院所等社会各方共同参与，广泛开展联合创新。</p>
        </div>
    </div>
</template>

<script >
import animated from 'animate.css' 
export default {
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
.Digital_JZ{
    width: 100%;
    height: 60vh;
    line-height: 2.8vh;
}

.JZ_bg{
    background-image: url('../../assets/images/dchina/jz.jpg');
    width: 45%;
    height: 46vh;
    background-size: 100% 46vh;
    float: left;
    margin: 5vh auto;
    /* position: relative; */
    /* box-shadow:rgb(5, 116, 228) 0 0 30px 5px; */
}

.JZ_ct{
    float: right;
    width: 54%;
    height: 45vh;
    background-size: 100% 45vh;
}

.JZ_ct p{
    text-indent: 2em;
    font-size: 16px;
    color: rgb(65, 62, 62);
}

</style>
