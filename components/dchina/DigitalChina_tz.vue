<template>
    <div class="Digital_TZ">
        <div class="TZ_bg"></div>
        <div class="TZ_ct">
            <center>
            <h2>“数字社会”运行状态的四个特征</h2></center><br/>
            <p>“数字社会”在其基本架构和整体运行上最为突出的一个特点就是它在数字化转换的前提下，
                依托互联网络，从最具有基础性意义的技术保障和运作机制层面，解决人们在社会生活中
                所必须要面对的一系列基本问题，得益于数字化、网络化和智能化的助推，建构起了活动
                平台和通行路径。“数字社会”和网络生活在运行状态上，显现出以下四个方面的本质特征。
            </p><br/>
            <p><b>第一、跨域连接与全时共在:</b>跨域连接首先解决的是普遍连接的问题。普遍连接既包括人与
                人之间的数字化连接，也包括智能设备与智能设备等物与物之间的数字化连接，还包括依托
                数字化而实现的人、物、智能设备相互之间的连接和贯通。
            </p><br/>
            <p><b>第二、行动自主与深入互动:</b>数字社会、网络时代和赛博空间，客观上为作为社会生活之行为
                主体的人的行为活动自由，提供了极为便利的基础条件。</p><br/>
            <p><b>第三、数据共享与资源整合:</b>网络世界贯通的是一个个的人、一台台的电脑和移动终端设备以
                及一个个的大型服务器和数据库。在某种意义上讲，网络空间，其实就是一个信息数据不断生
                成、存储、流转和分享的特定空间。</p><br/>
            <p><b>第四、智能操控与高效协作:</b>机械化、自动化和智能化的实现，是科学技术进步带给人类社会生
                活的“福利”。</p>
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
.Digital_TZ{
    width: 100%;
    height: 60vh;
}
.TZ_bg{
    background-image: url('../../assets/images/dchina/tz.jpg');
    width: 45%;
    height: 45vh;
    background-size: 100% 45vh;
    float: left;
    margin: 5vh auto;
    /* position: relative; */
    /* box-shadow:rgb(5, 116, 228) 0 0 30px 5px; */
}

.TZ_ct{
    float: right;
    width: 54%;
    height: 50vh;
    background-size: 100% 50vh;
}

.TZ_ct p{
    text-indent: 2em;
    font-size: 16px;
    color: rgb(65, 62, 62);
}

</style>
