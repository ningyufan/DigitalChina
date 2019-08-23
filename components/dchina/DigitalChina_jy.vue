<template>
    <div class="Digital_JY">
        <div class="JY_bg"></div>
        <div class="JY_ct">
            <center>
            <h2>共享机遇 共谋发展——数博会加速中国大数据产业融合创新</h2></center><br/>
            <!-- <p>初夏时节，万物葱茏。为期4天的2019中国国际大数据产业博览会在贵阳落下帷幕。作为全球首个
                大数据主题博览会，数博会已经走过5个年头，每年都促成了一批项目签约，产生了许多前沿思想。
            </p><br/> -->
            <p><b>第一、数字经济增添活力:</b>“我们大力推动大数据与实体经济深度融合，实施‘万企融合’和
            ‘百企引领’大行动，每年建设100个融合标杆项目、1000个融合示范项目，计划用3到5年时间，带动1万
            户以上实体经济企业与大数据深度融合，推动传统产业数字化、网络化、智能化转型。”贵州省大数据发
            展管理局副局长娄松说。
            </p><br/>
            <p><b>第二、数据互通共享助力精准扶贫:</b>中国一直是世界减贫事业的积极倡导者和有力推动者。
            2019年数博会延续此前对脱贫攻坚领域的关注，首次举办了“大数据与全球减贫”高端对话。“我亲眼看
            到了中国的减贫成效，很了不起。”联合国开发计划署驻华代表处副代表戴文德在高端对话上说。在他
            看来，中国的减贫成效来之不易，其在运用大数据精准定位贫困人口，精准找到致贫原因并提供解决方
            案上，对世界减贫具有借鉴意义。</p><br/>
            <p><b>第三、国际合作“朋友圈”越来越广:</b>纵观每届数博会，参会规模、会议成果等一项项纪录
            不断被刷新。今年，参展企业达到448家，其中境外参展企业达到156家。5年来，借助数博会，苹果、
            戴尔等世界500强企业进入中国更多业务领域。印度国家信息技术学院中国区域技术总监升迪说，
            去年数博会上，中印IT产业集聚区和大数据培训学院正式落户贵阳，印度大数据企业期待以贵州为桥头堡，
            进入中国发展。在科技领域，尤其是大数据发展方面，没有开放是不行的。”中国科学院院士梅宏认为，
            在信息时代要构建人类命运共同体，也要构建网络空间命运共同体，在开放中加强联合创新、协同创新，
            在深化国际合作中实现互利共赢。</p><br/>
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
.Digital_JY{
    width: 100%;
    height: 60vh;
}

.JY_bg{
    background-image: url('../../assets/images/dchina/jy.jpg');
    width: 45%;
    height: 48vh;
    background-size: 100% 48vh;
    float: left;
    margin: 5vh auto;
}

.JY_ct{
    float: right;
    width: 54%;
    height: 45vh;
    background-size: 100% 50vh;
}

.JY_ct p{
    text-indent: 2em;
    font-size: 16px;
    color: rgb(65, 62, 62);
}

</style>
