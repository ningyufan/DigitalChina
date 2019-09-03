<template>
    <div class="DigitalGX">
       <el-carousel :interval="5000" arrow="always" height="60vh"  aos="zoom-in-up">
            <el-carousel-item v-for="(item,idx) in items" :key="idx">
                <el-row>
                <el-col class="left_col">
                    <div class="detail">
                        <p class="title"><a :href="item.href">{{item.title}}</a></p>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;{{ item.p }}</p>
                        <hr class="hr" />
                            <div>
                                <a :href="item.href" >查看内容>></a>
                            </div>
                    </div>   
                </el-col>
                <el-col class="right_col">
                    <a :href="item.href"><img :src="item.img_src" height="80%" width="100%" alt=""></a>
                </el-col>
            </el-row>
            </el-carousel-item>
        </el-carousel>
    </div>
</template>

<script>
export default {
    data() {
        return {
             items: [{
                    id:0,
                    title:'智慧城市',
                    href:'#box1',
                    img_src: require('../../assets/images/gx/h_pic1.png'),
                    p:'智慧城市是把新一代信息技术充分运用在城市中各行各业基于知识社会下一代创新（创新2.0）的城市信息化高级形态，实现信息化、工业化与城镇化深度融合，有助于缓解“大城市病”，提高城镇化质量，实现精细化和动态管理，并提升城市管理成效和改善市民生活质量。',
                },{
                    id:1,
                    title:'智慧旅游',
                    href:'#box2',
                    img_src: require('../../assets/images/gx/h_pic3.png'),
                    p:'智慧旅游，也被称为智能旅游。就是利用云计算、物联网等新技术，通过互联网/移动互联网，借助便携的终端上网设备，主动感知旅游资源、旅游经济、旅游活动、旅游者等方面的信息，及时发布，让人们能够及时了解这些信息，及时安排和调整工作与旅游计划，从而达到对各类旅游信息的智能感知、方便利用的效果。智慧旅游的建设与发展最终将体现在旅游体验、旅游管理、旅游服务和旅游营销的四个层面。',
                    
                },{
                    id:2,
                    title:'智慧生活',
                    href:'#box3',
                    img_src: require('../../assets/images/gx/h_pic4.png'),
                    p:'智慧生活是指人类生存过程中的各项生活的总和，一般指为幸福的意义而存在，生活实际上是对人生的一种诠释。智能生活平台可以自由的与主流智能家居品牌产品互通，任何时候，任何场合，家庭用户可以自由的通过无线链接Internet，直接上互联网远程查询到相关所需信息并具备社交互动特点。',
                   
                },{
                    id:3,
                    title:'智慧农业',
                    href:'#box4',
                    img_src: require('../../assets/images/gx/h_pic5.png'),
                    p:'智慧农业是农业中的智慧经济，或智慧经济形态在农业中的具体表现。智慧农业是智慧经济重要的组成部分；对于发展中国家而言，智慧农业是智慧经济主要的组成部分，是发展中国家消除贫困、实现后发优势、经济发展后来居上、实现赶超战略的主要途径。',
                    
                },{
                    id:4,
                    title:'智慧教育',
                    href:'#box5',
                    img_src: require('../../assets/images/gx/h_pic6.png'),
                    p:'智慧教育即教育信息化，是指在教育领域（教育管理、教育教学和教育科研）全面深入地运用现代信息技术来促进教育改革与发展的过程。其技术特点是数字化、网络化、智能化和多媒体化，基本特征是开放、共享、交互、协作、泛在。以教育信息化促进教育现代化，用信息技术改变传统模式。',
                    
                },{
                    id:5,
                    title:'数字广西',
                    href:'#box6',
                    img_src:require('../../assets/images/wuti.png'),
                    p:'数字广西是数字城市的重要组成部分。广西基础地理信息中心肩负着“数字广西”地理空间基础框架建设的任务。数字城市 [2]  是以计算机技术、多媒体技术和大规模存储技术为基础，以宽带网络为纽带，运用遥感、全球定位系统、地理信息系统、遥测、仿真-虚拟等技术，对城市进行多分辨率、多尺度、多时空和多种类的三维描述，即利用信息技术手段把城市的过去、现状和未来的全部内容在网络上进行数字化虚拟实现。',
                
                }]
        }
    }
}
</script>
<style>
.left_col{
    width: 70%;
    height: 60vh;
    float: left;
    color: rgb(48, 189, 245);
    font-family: STXingkai;
  }
  .right_col {
    width: 30%;
    height: 60vh;
    float: right;
    margin-top: 5vh;
  }
  .right_col img {
      transition: all 500ms linear;
  }

  .right_col img:hover {
      transform: scale(1.1,1.1)
  }
  .detail {
    margin: 10vh 8vw;
  }
  .detail .title{
    font-size: 4vh;
    text-align: center;
    margin: 2vh auto;
    font-family: STXingkai;
  
  }
  .detail p{
    font-size: 3vh;
    text-align: justify;
  }
  hr {
    margin: 3vh 0 3vh 0;
    height:1px;
    border:none;
    border-top:1px solid #6ec1e2;
  }
  .detail div {
      text-align: center;
  }
</style>