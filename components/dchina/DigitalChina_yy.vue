<template>
    <div class="Digital_YY">
        <div class="YY_bg"></div>
        <div class="YY_ct">
            <center>
            <h2>“数字经济”发展隐忧浮现</h2></center><br/>
            <p>随着大数据在国家治理、经济发展等方面的影响日益加深，数据安全问题逐渐凸显，个人信息泄露、
                网络诈骗给公民人身和财产安全带来威胁。进入“数字经济”时代，如何给数据安全“上锁”成为2019
                中国国际大数据产业博览会与会专家讨论的焦点。
            </p>
            <p><b>“数字经济”高速发展伴随安全隐忧:</b>中国信通院发布的《中国数字经济发展与就业白皮书（2019年）》
            显示，近年来我国“数字经济”规模保持快速增长，2018年我国数字经济总量达到31.3万亿元，占GDP比重超过1/3，
            达到34.8%，占比同比提升1.9个百分点。本届博览会发布的《中国大数据发展报告》显示，当前全球贸易已经有50%
            以上实现了数字化。数字经济时代，数据的集聚开发应用加大了个人隐私泄露、泄密的风险。此外，大数据本身也在
            帮助黑客来进行相应的数据分析。
            </p>
            <p><b>加快数据分层分级保护:</b>5月28日，国家网信办发布《数据安全管理办法（征求意见稿）》，就维护国家安全、
            社会公共利益，保护公民、法人和其他组织在网络空间的合法权益，保障个人信息和重要数据安全，征求广大网民意见。
            继《中华人民共和国网络安全法》颁布实施后，2018年《个人信息保护法》被列入五年立法规划，2019年《中华人民共和国数据安全法》
            被列入年度立法规划。</p>
            <p><b>全面提升数据安全保障能力:</b>与会专家指出，应建立管理、技术、运营、监管四个维度，平台、数据、应用三个层次的全方位
            数据安全防护体系。要突破和掌握大数据安全治理的核心关键技术，着力推动在大数据背景下的技术创新。通过加大研发和创新力度，
            提高数据安全预警、溯源能力，以及应急和处置能力。加强数据防泄露、防窃取、数据加密等技术的研发。数据安全人才短缺的现象
            也是与会专家关注的焦点，尤其是如何加快培养政企机构急需的安全分析型人才。</p><br/>
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
.Digital_YY{
    width: 100%;
    height: 60vh;
}
.YY_bg{
    background-image: url('../../assets/images/dchina/yy.jpg');
    width: 45%;
    height: 45vh;
    background-size: 100% 45vh;
    float: left;
    margin: 8vh auto;
    /* position: relative; */
    /* box-shadow:rgb(5, 116, 228) 0 0 30px 5px; */
}

.YY_ct{
    float: right;
    width: 54%;
    height: 50vh;
    background-size: 100% 50vh;
}

.YY_ct p{
    text-indent: 2em;
    font-size: 16px;
    color: rgb(65, 62, 62);
}

</style>
