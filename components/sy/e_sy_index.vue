<template>
    <div class="sy_index">
        <div id="particles-js"></div>
        
        <div id="sy_box1" class="sy_box1">
            <esyBox1/>
        </div>
        <div class="sy_box2">
            
            <esyBox2/>
        </div>
        <div class="sy_box3">
            
            <esyBox3/>
        </div>
        <div class="sy_box4">
            
            <esyBox4/>
        </div>
        <div class="sy_box5">
            
            <esyBox5/>
        </div>

    </div>
</template>

<script>
import esyBox1 from './e_sy_box1'
import esyBox2 from './e_sy_box2'
import esyBox3 from './e_sy_box3'
import esyBox4 from './e_sy_box4'
import esyBox5 from './e_sy_box5'
export default {
    components: {
        esyBox1,
        esyBox2,
        esyBox3,
        esyBox4,
        esyBox5,
    },
    head:{
        script:[
            // {src:'js/jquery.1.7.1.min.js'},//aos
            // {src:'js/aos.js'},//aos
            {src:'js/particles.min.js'},//背景动画
            // {src:'js/index.js'},//box2_style
        ],
        link: [
            // { rel: 'stylesheet', href: 'css/normalize.css' },//aos
            // { rel: 'stylesheet', href: 'js/aos.css' },//aos
            // { rel: 'stylesheet', href: 'css/styles.css' },//aos
            { rel: 'stylesheet', href: 'https://fonts.googleapis.com/css?family=Open+Sans' },//box2_style
            { rel: 'stylesheet', href: 'css/style2.css' },//box2_style
        ]
    },
    created() {
    },

    mounted() {
        // AOS.init({
        //     easing: 'ease-in-out',
        //     duration: 500,
		// 	once :false
        // });
        particlesJS('particles-js',{
            "particles": {
                "number": {
                "value": 160,//数量
                "density": {
                    "enable": true, //启用粒子的稀密程度
                    "value_area": 800 //区域散布密度大小
                }
                },
                "color": {
                "value": "#00aeff" //原子的颜色
                },
                "shape": {
                "type": "circle", //原子的形状 "circle" ,"edge" ,"triangle" ,"polygon" ,"star" ,"image" ,["circle", "triangle", "image"]
                "stroke": {
                    "width": 0, //原子的宽度
                    "color": "#362cff" //原子颜色
                },
                "polygon": {
                    "nb_sides": 5 // 原子的多边形边数
                },
                "image": {
                    "src": "img/github.svg", // 原子的图片可以使用自定义图片 "assets/img/yop.svg" , "http://mywebsite.com/assets/img/yop.png"
                    "width": 100, //图片宽度
                    "height": 100 //图片高度
                }
                },
                "opacity": {
                "value": 1, //不透明度
                "random": true, //随机不透明度
                "anim": {
                    "enable": true, //渐变动画
                    "speed": 1, // 渐变动画速度
                    "opacity_min": 0, //渐变动画不透明度
                    "sync": true 
                }
                },
                "size": {
                "value": 3, //原子大小
                "random": true, // 原子大小随机
                "anim": {
                    "enable": false, // 原子渐变
                    "speed": 4, //原子渐变速度
                    "size_min": 0.3, 
                    "sync": false
                }
                },
                "line_linked": {
                "enable": false, //连接线
                "distance": 150, //连接线距离
                "color": "#ffffff", //连接线颜色
                "opacity": 0.4, //连接线不透明度
                "width": 1 //连接线的宽度
                },
                "move": {
                "enable": true, //原子移动
                "speed": 1, //原子移动速度
                "direction": "none", //原子移动方向   "none" ,"top" ,"top-right" ,"right" ,"bottom-right" ,"bottom" ,"bottom-left" ,"left" ,"top-left"
                "random": true, //移动随机方向
                "straight": false, //直接移动
                "out_mode": "out", //是否移动出画布
                "bounce": false, //是否跳动移动
                "attract": { 
                    "enable": false, // 原子之间吸引
                    "rotateX": 600, //原子之间吸引X水平距离
                    "rotateY": 600  //原子之间吸引Y水平距离
                }
                }
            },
            "interactivity": {
                "detect_on": "canvas", //原子之间互动检测 "canvas", "window"
                "events": {
                "onhover": {
                    "enable": true, //悬停
                    "mode": "bubble" //悬停模式      "grab"抓取临近的,"bubble"泡沫球效果,"repulse"击退效果,["grab", "bubble"]
                },
                "onclick": {
                    "enable": false,  //点击效果
                    "mode": "repulse"  //点击效果模式   "push" ,"remove" ,"bubble" ,"repulse" ,["push", "repulse"]
                },
                "resize": true // 互动事件调整
                },
                "modes": {
                "grab": {
                    "distance": 100, //原子互动抓取距离
                    "line_linked": { 
                    "opacity": 0.8  //原子互动抓取距离连线不透明度
                    }
                },
                "bubble": {
                    "distance": 250, //原子抓取泡沫效果之间的距离
                    "size": 4, // 原子抓取泡沫效果之间的大小
                    "duration": 2, //原子抓取泡沫效果之间的持续事件
                    "opacity": 1, //原子抓取泡沫效果透明度
                    "speed": 3 
                },
                "repulse": {
                    "distance": 400, //击退效果距离
                    "duration": 0.4 //击退效果持续事件
                },
                "push": {
                    "particles_nb": 4 //粒子推出的数量
                },
                "remove": {
                    "particles_nb": 2
                }
                }
            },
            "retina_detect": true
            }

        );
        


    },

}
</script>

<style>
@import "@/assets/css/sy/sy.css";

canvas{
  display:block;
  vertical-align:bottom;
}


/* ---- stats.js ---- */

.count-particles{
  /* background: #000022; */
  position: absolute;
  top: 48px;
  left: 0;
  width: 80px;
  color: #13E8E9;
  font-size: .8em;
  text-align: left;
  text-indent: 4px;
  line-height: 14px;
  padding-bottom: 2px;
  font-family: Helvetica, Arial, sans-serif;
  font-weight: bold;
}

.js-count-particles{
  font-size: 1.1em;
}

#stats,
.count-particles{
  -webkit-user-select: none;
  margin-top: 5px;
  margin-left: 5px;
}

#stats{
  border-radius: 3px 3px 0 0;
  /* overflow: hidden; */
}

.count-particles{
  border-radius: 0 0 3px 3px;
}


/* ---- particles.js container ---- */

#particles-js{
    position: absolute;
    left: 0;
    top: 0;
    width: 100%;
    height: 100%;
    /* background-color: #000000; */
    /* background-image: url(''); */
    background-size: cover;
    background-position: 50% 50%;
    background-repeat: no-repeat;
}
</style>
