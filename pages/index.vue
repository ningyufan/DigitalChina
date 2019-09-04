<template>
  <div class="homepage-hero-module">
    <div class="video-container">
      <div :style="fixStyle" class="filter">
          <div class="title wow bounceInDown">
             <p style="font-family:duanning;" id="Title">人民对美好生活的向往,就是数字中国建设的优先行动方向</p>
          </div>
           <div class="but-box">
             <div>
               <p class="chinese wow bounceInLeft">
                 <a class="index_a" href="/chinese_index">中文</a>
              </p>
             </div>
             <div>
              <p class="english wow bounceInRight">
                 <a class="index_a" href="/english_index">English</a>
              </p> 
             </div>
           </div>
      </div>
      <video
        :style="fixStyle"
        autoplay loop muted
        lass="fillWidth" 
        v-on:canplay="canplay"
        >
          <source src="../assets/video/index_video.mp4" type="video/mp4"/>
          浏览器不支持 video 标签，建议升级浏览器。
          <source src="../assets/video/index_video.mp4" type="video/webm"/>
          浏览器不支持 video 标签，建议升级浏览器。
      </video>

      <audio src="/index.mp3" controls="controls" autoplay="autoplay" loop  style="position: relative; z-index:5;" >
        <source src="/index.mp3" type="audio/ogg" />
        <source src="/index.mp3" type="audio/mpeg"/>
      </audio>


      <div class="poster hidden" v-if="!vedioCanPlay">
        <img :style="fixStyle" alt="">
      </div>
    </div>
  </div>
</template>


<script>
  if (process.browser) { // 在这里根据环境引入wow.js
      var {WOW} = require('wowjs')
  }
  export default {
    components: {
      // Video
    },
    data() {
      return {
        vedioCanPlay: false,
        fixStyle: '',
      }
    },
    head:{
            script:[
                {src:'js/jquery.1.7.1.min.js'},
                {src:'js/aos.js'},
            ],
            link: [
		          { rel: 'stylesheet', href: 'css/normalize.css' },
              { rel: 'stylesheet', href: 'js/aos.css' },
              { rel: 'stylesheet', href: 'css/styles.css' }
		    ]
    },
    methods: {
      canplay() {
        this.vedioCanPlay = true
      }
    },
    mounted: function() {

      AOS.init({
        easing: 'ease-out-back',
        duration: 1000
      });
      if (process.browser) {  // 在页面mounted生命周期里面 根据环境实例化WOW
         new WOW({
             live: false, 
             offset: 0
         }).init()
     } 
      window.onresize = () => {
        const windowWidth = document.body.clientWidth
        const windowHeight = document.body.clientHeight
        const windowAspectRatio = windowHeight / windowWidth
        let videoWidth
        let videoHeight
        if (windowAspectRatio < 0.5625) {
          videoWidth = windowWidth
          videoHeight = videoWidth * 0.5625
          this.fixStyle = {
            height: windowWidth * 0.5625 + 'px',
            width: windowWidth + 'px',
            'margin-bottom': (windowHeight - videoHeight) / 2 + 'px',
            'margin-left': 'initial'
          }
        } else {
          videoHeight = windowHeight
          videoWidth = videoHeight / 0.5625
          this.fixStyle = {
            height: windowHeight + 'px',
            width: windowHeight / 0.5625 + 'px',
            'margin-left': (windowWidth - videoWidth) / 2 + 'px',
            'margin-bottom': 'initial'
          }
        }
      }
      window.onresize()
    }
  }
</script>

<style scoped>
  @import "@/assets/css/index/page_index.css";
  @import "@/assets/css/yulin/font_index.css";

  #Title {
  animation: layerize cubic-bezier(0.4, 0, 0.2, 1) 1200ms 200ms forwards;
  opacity: 0;
  width: 100%;
  color: #fff;
  font: italic 6vh 15rem "Roboto", sans-serif;
  cursor: default;
  user-select: none;
  text-align: center;
}

@keyframes layerize {
  0% {
    opacity: 0;
    transform: translate(0, 0);
    text-shadow: none;
  }
  100% {
    opacity: 1;
    transform: translate(-0.06667em, -0.06667em);
    text-shadow: 0 0 transparent, 0.03333em 0.03333em rgba(255, 255, 255, 0.4), 0.06667em 0.06667em rgba(255, 255, 255, 0.3), 0.1em 0.1em rgba(255, 255, 255, 0.2), 0.13333em 0.13333em rgba(255, 255, 255, 0.1);
  }
}
</style>
