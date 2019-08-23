<template>
    <div class="Digital_GJ">
        <div class="GJ_bg"></div>
        <div class="GJ_ct">
            <center>
            <h2>“大数据”融合贯通 让生活更便捷</h2></center><br/>
            <p>2019中国国际大数据产业博览会正在贵阳举行，大数据如何应用成为人们关注的焦点。“大数据”的融合
                贯通，让分散的数据孤岛被打通，我们的生产、生活正在发生全新的变化。这样就会逐渐实现贵州省
                提出的进一张网办全省事。目前，贵州省400多个高频和热点的事情都可以在手机上办理，比如说：
                代开发票、出生医学证明补办等等。如果我开车出门忘带驾驶证也不要紧，刚刚上线的身份证、
                驾驶证的电子证照，只要打开手机进入移动端点击驾驶证，通过张张嘴点点头和摇摇头，就可以生成
                这样的电子证照交给交警了。
            </p><br/>
            <p>在展览区，大数据的应用随处可见，给我们更直观的感受就是大数据让我们的生活更便捷更智慧。
                在我旁边的云上贵州数字政务平台上，已经汇聚了贵州省9个市州40多个省直部门9000多个应用融合。
                目前，利用大数据和人工智能等技术，贵州正在努力尝试让云上贵州数据平台，具备自我学习的能力，变得更加智能。
            </p><br/>
            <p>而政府各个部门、以及企业和个人的数据要实现共享和交换，最重要的就是保证安全。在本届数博会上，一套由我国自
                主研发的“数据交换二维码摆渡系统”正式推出。它利用“模拟人眼识别”和独特的“高速二维码编解码技术”，不但实现内、
                外网物理隔断，同时兼顾数据传输的安全、高效。</p>
            
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
.Digital_GJ{
    width: 100%;
    height: 60vh;
}

.GJ_bg{
    background-image: url('../../assets/images/dchina/ronghe.png');
    width: 46%;
    height: 46vh;
    background-size: 100% 46vh;
    float: left;
    margin: 5vh auto;
    /* position: relative; */
    /* box-shadow:rgb(5, 116, 228) 0 0 30px 5px; */
}

.GJ_ct{
    float: right;
    width: 52%;
    height: 46vh;
    background-size: 100% 46vh;
}

.GJ_ct p{
    text-indent: 2em;
    font-size: 16px;
    color: rgb(65, 62, 62);
}

</style>
