<template>
    <div class="Digital_video">
        <el-row class="Video_row1 wow bounceInRight">
            <el-col class="Video_col1">
                <section>
                    <video controls="controls">
                        <source src="@/assets/video/guiyang_sz.mp4" type="video/mp4">
                    </video>
                    <div class="video_ct">
                        <p>[第一时间]数博会国际化水平大幅提升大数据加速贵阳经济发展</p>
                    </div>
                </section>
            </el-col>
            <el-col class="Video_col2">
                <section>
                    <video controls="controls">
                        <source src="@/assets/video/guizhou_ncp.mp4" type="video/mp4">
                    </video>
                    <div class="video_ct">
                        <p>[第一时间]聚焦2019贵阳数博会数博会首设扶贫展大数据牵手“农产品”</p>
                    </div>
                </section>
            </el-col>
            <el-col class="Video_col3">
                <section>
                    <video controls="controls">
                        <source src="@/assets/video/guizhou_jjrh.mp4" type="video/mp4">
                    </video>
                    <div class="video_ct">
                        <p>[贵州新闻联播]大数据与实体经济深度融合全国行首站在贵阳启动</p>
                    </div>
                </section>
            </el-col>
        </el-row>
        <el-row class="Video_biaoti wow zoomIn" data-wow-delay="1s">
            <h3 class="biaoti">看大数据推进“社会经济”发展</h3>
        </el-row>
        <el-row class="Video_row2 wow bounceInLeft">
            <el-col class="Video_col4">
                <section>
                    <video controls="controls">
                        <source src="@/assets/video/guizhou_xcjj.mp4" type="video/mp4">
                    </video>
                    <div class="video_ct">
                        <p>[经济信息联播]聚焦2019贵阳数博会贵州：大数据助力乡村经济发展</p>
                    </div>
                </section>
            </el-col>
            <el-col class="Video_col5">
                <section>
                    <video controls="controls">
                        <source src="@/assets/video/jjgzlfz.mp4" type="video/mp4">
                    </video>
                    <div class="video_ct">
                        <p>[中国新闻]聚焦中国两会贵州：发展大数据让经济高质量发展</p>
                    </div>
                </section>
            </el-col>

            <el-col class="Video_col6">
                <section>
                    <video controls="controls">
                        <source src="@/assets/video/guizhou_jjrh.mp4" type="video/mp4">
                    </video>
                    <div class="video_ct">
                        <p>[贵州新闻联播]大数据与实体经济深度融合全国行首站在贵阳启动</p>
                    </div>
                </section>
            </el-col>
        </el-row>
    </div>
</template>

<script>

  import animated from 'animate.css' 
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
        Video
    },
    methods: {
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
        offset:120,
        easing: 'ease-out-back',
        duration: 1000,
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
    }

}
</script>

<style>
    @import "@/assets/css/digital_china.css";

.video_ct{
  position:absolute;
  width: 70%;
  color:#ffffff;
  font-family:"微软雅黑";
  font-size:20px;
  opacity: 0;
  transition: all 0.5s;
 }

 .Video_biaoti{
    margin: 8vh 0 4vh 70vh;
    color: rgb(48, 189, 245);
    font-family:"微软雅黑";
    font-size:28px;
 }

 .Video_biaoti .biaoti:hover{
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

</style>
