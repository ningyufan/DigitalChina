<template>
    <div class="anli">
    <div class="bt02" aos="zoom-in">
      <h2>看“数字经济”</h2>
    </div>
          <span>
            <div class="al01 al wow bounceInRight" @click="VideoVisible1=true"></div>
            <el-dialog :visible.sync="VideoVisible1">
                <video controls="controls" width="100%">
                    <source src="@/assets/video/china_video1.mp4" type="video/mp4">
                </video>
                <h3>[第一时间]数博会国际化水平大幅提升大数据加速贵阳经济发展</h3>
            </el-dialog>
         </span>
          <span>
            <div class="al06 al wow bounceInRight" @click="VideoVisible2=true"></div>
            <el-dialog :visible.sync="VideoVisible2">
                <video controls="controls" width="100%">
                    <source src="@/assets/video/china_video2.mp4" type="video/mp4">
                </video>
                <h3>[中国新闻]聚焦中国两会贵州：发展大数据让经济高质量发展</h3>
            </el-dialog>
         </span>
          <span>
            <div class="al02 al wow bounceInRight" @click="VideoVisible3=true"></div>
            <el-dialog :visible.sync="VideoVisible3">
                <video controls="controls" width="100%">
                    <source src="@/assets/video/china_video3.mp4" type="video/mp4">
                </video>
                <h3>[第一时间]聚焦2019贵阳数博会数博会首设扶贫展大数据牵手“农产品”</h3>
            </el-dialog>
         </span>
          <span>
            <div class="al03 al wow bounceInLeft" @click="VideoVisible4=true"></div>
            <el-dialog :visible.sync="VideoVisible4">
                <video controls="controls" width="100%">
                    <source src="@/assets/video/china_video4.mp4" type="video/mp4">
                </video>
                <h3>[贵州新闻联播]大数据与实体经济深度融合全国行首站在贵阳启动</h3>
            </el-dialog>
         </span>
          <span>
            <div class="al04 al wow bounceInLeft" @click="VideoVisible5=true"></div>
            <el-dialog :visible.sync="VideoVisible5">
                <video controls="controls" width="100%">
                    <source src="@/assets/video/china_video5.mp4" type="video/mp4">
                </video>
                <h3>[经济信息联播]聚焦2019贵阳数博会贵州：大数据助力乡村经济发展</h3>
            </el-dialog>
         </span>
          <span>
            <div class="al05 al wow bounceInLeft" @click="VideoVisible6=true"></div>
            <el-dialog :visible.sync="VideoVisible6">
                <video controls="controls" width="100%">
                    <source src="@/assets/video/china_video6.mp4" type="video/mp4">
                </video>
                <h3>[视频]贵州：大数据产业推动社会经济发展</h3>
            </el-dialog>
         </span>
  </div>
</template>

<script>
import animated from 'animate.css' 
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
    data(){
        return{
            VideoVisible1: false,VideoVisible2: false,
            VideoVisible3: false,VideoVisible4: false,
            VideoVisible5: false,VideoVisible6: false
        }
    },
    methods:{
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
    @import "@/assets/css/digital_china.css";

.anli{
    position: relative;
    width: 100%;
    margin:10vh auto 5vh 20vh;
    height: 100vh;
    font-family: "微软雅黑";
}

.anli .bt02{
    position: absolute;
	text-align: center;
	font-family: "微软雅黑";
	width:  100%;
	height: 5vh;
	right: 8vw;
}
.anli .bt02 h2{
   line-height:5vh;
   font-size: 5vh;
   color: rgb(48, 189, 245);
}

.anli .bt02 h2:hover{
    animation: biaoti 1s linear 3;
}

 @keyframes biaoti{
    33.3%{
        font-size: 4vh;
    }
    66.6%{
        font-size: 4.5vh;
    }
    99.9%{
        font-size: 4vh;
    }
}

.al{
    box-shadow:#1E90FF 0 0 30px 5px;
    border-radius: 4px;
    float: left;
    width: 20vw;
    height: 25vh;
    margin: 90px 10px 0px 10px;
    overflow: hidden;
    -moz-transition:all 1s ease;
    -webkit-transition:all 1s ease;
    -o-transition:all 1s ease;
    -ms-transition:all 1s ease;
    transition:all 1s ease;
}
.al01{
    border: 2px solid #bcb4b4;
    background:url("../../assets/images/dchina/video1.jpg")no-repeat center; 
    background-size: cover;
}
.al02{
    border: 2px solid #bcb4b4;
    background:url("../../assets/images/dchina/video2.jpg") no-repeat center; 
    background-size: cover;
}
.al03{
    clear: both;
    border: 2px solid #bcb4b4;
    background:url("../../assets/images/dchina/video3.jpg") no-repeat center; 
    background-size: cover;
}
.al04{
    margin-left:140px; 
    margin-right:140px; 
    border: 2px solid #bcb4b4;
    background:url("../../assets/images/dchina/video4.jpg") no-repeat center; 
    background-size: cover;
}
.al05{
    background:url("../../assets/images/dchina/video5.jpg") no-repeat center; 
    border: 2px solid #bcb4b4;
    background-size: cover;
}
.al06{
    margin-left:140px; 
    margin-right:140px; 
    border: 2px solid #bcb4b4;
    background:url("../../assets/images/dchina/video6.jpg") no-repeat center; 
    background-size: cover;
}
.al01:hover{
    -moz-transform:scale(2.6) translate(160px, 49px);
    -webkit-transform:scale(2.6) translate(160px, 49px);
    -o-transform:scale(2.6) translate(160px, 49px);
    -ms-transform:scale(2.6) translate(160px, 49px);
    transform:scale(2.6) translate(160px, 49px);
    z-index:2;
}
.al06:hover{
    -moz-transform:scale(2.6) translate(0, 50px);
    -webkit-transform:scale(2.6) translate(0, 50px);
    -o-transform:scale(2.6) translate(0, 50px);
    -ms-transform:scale(2.6) translate(0, 50px);
    transform:scale(2.6) translate(0, 50px);
}
.al02:hover{
    -moz-transform:scale(2.6) translate(-160px, 50px);
    -webkit-transform:scale(2.6) translate(-160px, 50px);
    -o-transform:scale(2.6) translate(-160px, 50px);
    -ms-transform:scale(2.6) translate(-160px, 50px);
    transform:scale(2.6) translate(-160px, 50px);
}
.al03:hover{
    -moz-transform:scale(2.6) translate(160px, -50px);
    -webkit-transform:scale(2.6) translate(160px, -50px);
    -o-transform:scale(2.6) translate(160px, -50px);
    -ms-transform:scale(2.6) translate(160px, -50px);
    transform:scale(2.6) translate(160px, -50px);
}
.al04:hover{
    -moz-transform:scale(2.6) translate(0, -38px);
    -webkit-transform:scale(2.6) translate(0, -50px);
    -o-transform:scale(2.6) translate(0, -38px);
    -ms-transform:scale(2.6) translate(0, -50px);
    transform:scale(2.6) translate(0, -50px);
}
.al05:hover{
    -moz-transform:scale(2.6) translate(-160px, -50px);
    -webkit-transform:scale(2.6) translate(-160px, -50px);
    -o-transform:scale(2.6) translate(-160px, -50px);
    -ms-transform:scale(2.6) translate(-160px, -50px);
    transform:scale(2.6) translate(-160px, -50px);
}

/* .anli .al h3{
  font-size: 18px;
  color: #ffffff;
  margin:0;
  text-align: center;
  padding-top: 140px;
} */



</style>
