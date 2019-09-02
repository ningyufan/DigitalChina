<template>
    <div class="cn_header">
       <el-carousel :interval="5000" arrow="always" height="60vh" aos="zoom-in-up">
            <el-carousel-item v-for="(item,idx) in items" :key="idx">
                <el-row>
                <el-col class="cn_left_col">
                    <div class="cn_detail">
                        <p class="title"><a :href="item.href">{{item.title}}</a></p>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{{ item.p }}</p>
                        <hr class="hr" />
                            <div>
                                <a :href="item.href" style="font-size:2.5vh;font-family: STXingkai;">查看内容>></a>
                            </div>
                    </div>   
                </el-col>
                <el-col class="cn_right_col">
                    <a :href="item.href"><img :src="item.img_src" height="70%" width="80%" alt="" style="border-radius:100%;"></a>
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
                    title:'机遇挑战',
                    href:'#cnbg1',
                    img_src: require('../../assets/images/dchina/tz.jpg'),
                    p:'中国数字经济的崛起势如破竹：中国占全球电子商务的比重已经高达42%；全世界最成功的科技初创企业有三分之一在中国；中国每年的移动支付总额更是美国的11倍。 中国数字经济的迅猛发展要归功于其丰富多样的创新创业生态系统、监管者和政府对技术发展的友好态度，以及巨大的消费市场。中国有7.31亿互联网用户，比欧盟和美国的总和还要多......',
                },{
                    id:1,
                    title:'推动新发展',
                    href:'#cnbg2',
                    img_src: require('../../assets/images/dchina/szjj1.png'),
                    p:'在新一轮科技革命和产业变革蓄势待发时期，我国数字经济规模持续扩大。根据中国信息通信产业研究院发布的《中国数字经济发展与就业白皮书（2019年）》显示，2018年中国数字经济规模达到31.3万亿元，占GDP比重为34.8%......',
                    
                },{
                    id:2,
                    title:'推动城市发展',
                    href:'#cnbg3',
                    img_src: require('../../assets/images/dchina/szjj9.jpg'),
                    p:'智慧城市是把新一代信息技术充分运用在城市中各行各业基于知识社会下一代创新（创新2.0）的城市信息化高级形态，实现信息化、工业化与城镇化深度融合，有助于缓解“大城市病”，提高城镇化质量，实现精细化和动态管理，并提升城市管理成效和改善市民生活质量.....',
                   
                },{
                    id:3,
                    title:'智慧中国',
                    href:'#cnbg4',
                    img_src: require('../../assets/images/dchina/szzg.jpg'),
                    p:'数字中国旨在以遥感卫星图像为主要的技术分析手段，在可持续发展、农业、资源、环境、全球变化、生态系统、水土循环系统等方面管理中国。但的十九大报告中的数字中国是更加广义的概念，是中国的国家信息化范畴，“宽带 中国”“互联网 ”“大数据”“云计算 ”等都是数字中国的内容。',
                    
                },{
                    id:4,
                    title:'看“数字经济”',
                    href:'#cnbg5',
                    img_src: require('../../assets/images/dchina/szjj.jpg'),
                    p:'聚焦数博会，看数字中国发展，看大数据在各个领域上的应用。大数据产业推动着社会的发展，继续推进城市的新发展，建设智慧城市，继续推进经济的高速平稳发展......',
                    
                },{
                    id:5,
                    title:'县域经济发展',
                    href:'#cnbg6',
                    img_src:require('../../assets/images/dchina/cn2.png'),
                    p:'互联网、云计算、大数据、物联网等飞速更新的信息通讯技术正深刻重塑着交通、医疗、农业、金融、通信、社会治理等应用场景。同时，随着智慧城市建设不断引向深入，智慧城市发展明显呈现出从大中城市向中小城市，尤其是向县域地区普及的发展态势......',
                
                }]
        }
    }
}
</script>
<style>
.cn_left_col{
    width: 70%;
    height: 60vh;
    float: left;
  
  }
  .cn_right_col {
    width: 30%;
    height: 60vh;
    margin-top: 6vh;
    float: right;
  }
  .cn_detail {
    margin: 10vh 8vw;
  }
  .cn_detail .title{
    font-size: 4vh;
    margin: 2vh auto;
    text-align: center;
    font-family: STXingkai;
  
  }
  .cn_detail p{
    font-size: 3vh;
     text-align:justify;
     font-family: STXingkai;
    color:rgb(51, 135, 214);
  }
  hr {
    margin: 3vh 0 3vh 0;
    height:1px;
    border:none;
    border-top:1px solid #6ec1e2;
  }
  .cn_detail div {
      text-align: center;
  }
</style>