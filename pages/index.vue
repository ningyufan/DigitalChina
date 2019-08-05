<template>
  <div class="homepage-hero-module">
    <div class="video-container">
      <div :style="fixStyle" class="filter">
          <div class="title wow bounceInDown">
             <p>人民对美好生活的向往,就是数字中国建设的优先行动方向</p>
          </div>
           <div class="but-box">
             <div>
               <p class="chinese wow bounceInLeft">
                 <nuxt-link to="/chinese_index">中文</nuxt-link>
              </p>
             </div>
             <div>
              <p class="english wow bounceInRight">
                 <nuxt-link to="/english_index">English</nuxt-link>
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
          <source src="../assets/video/Chinesemap.mp4" type="video/mp4"/>
          浏览器不支持 video 标签，建议升级浏览器。
          <source src="../assets/video/Chinesemap.mp4" type="video/webm"/>
          浏览器不支持 video 标签，建议升级浏览器。
      </video>
      <div class="poster hidden" v-if="!vedioCanPlay">
        <img :style="fixStyle" src="PATH_TO_JPEG" alt="">
      </div>
    </div>
  </div>
</template>

<script src="https://cdn.staticfile.org/vue/2.2.2/vue.min.js"></script>
<script>
  import Video from 'video.js'
  if (process.browser) { // 在这里根据环境引入wow.js
      var {WOW} = require('wowjs')
  }
  export default {
    components: {
      Video
    },
    data() {
      return {
        vedioCanPlay: false,
        fixStyle: '',
      }
    },
    methods: {
      canplay() {
        this.vedioCanPlay = true
      }
    },
    mounted: function() {
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
</style>
