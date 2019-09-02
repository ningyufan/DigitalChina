<template>
    <div class="sy_header">
       <el-carousel :interval="5000" arrow="always" height="60vh">
            <el-carousel-item v-for="(item,idx) in items" :key="idx">
                <el-row>
                <el-col class="sy_left_col">
                    <div class="sy_detail">
                        <p class="title"><a :href="item.href">{{item.title}}</a></p>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{{ item.p }}</p>
                        <hr class="hr" />
                            <div>
                                <a :href="item.href" style="font-size:2.5vh; font-family: STXingkai;">查看内容>></a>
                            </div>
                    </div>   
                </el-col>
                <el-col class="sy_right_col">
                    <a :href="item.href"><img :src="item.img_src" height="60%" width="80%" alt="" style="border-radius:100%;"></a>
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
                    title:'数字中国',
                    href:'#sy_box1',
                    img_src: require('../../assets/images/sy/map1.png'),
                    p:'数字中国旨在以遥感卫星图像为主要的技术分析手段，在可持续发展、农业、资源、环境、全球变化、生态系统、水土循环系统等方面管理中国。',
                },{
                    id:1,
                    title:'数字行业',
                    href:'#sy_box2',
                    img_src: require('../../assets/images/sy/map2.png'),
                    p:'数字产业是指以信息为加工对象，以数字技术为加工手段，以意识（广义的意识概念）产品为成果，以介入全社会各领域为市场，对本身无明显利润但是可以提升其他产业利润的公共产业。',
                    
                },{
                    id:2,
                    title:'数字动态',
                    href:'#sy_box3',
                    img_src: require('../../assets/images/sy/map3.png'),
                    p:'中国第二届数字建设峰会在今年的五月初开幕，“数字中国建设峰会”是中国信息化发展政策发布平台、电子政务和数字经济发展成果展示平台、数字中国建设理论经验和实践交流平台。今年也是5G元年，5G的到来推进了数字中国的发展。',
                   
                },{
                    id:3,
                    title:'数字人物',
                    href:'#sy_box4',
                    img_src: require('../../assets/images/sy/map4.png'),
                    p:'在数字中国的发展过程中涌现出一批批数字的领军人物，引领数字发展，提出的建议促进数字中国的发展。',
                    
                },{
                    id:4,
                    title:'5G时代',
                    href:'#sy_box5',
                    img_src: require('../../assets/images/sy/map5.png'),
                    p:'5G时代是第七次信息革命是智能互联网，5G是第七次信息革命的基础。5G被誉为“数字经济新引擎”，既是人工智能、物联网、云计算、区块链、视频社交等新技术新产业的基础，也将为“中国制造2025”和“工业4.0”提供关键支撑。',
                    
                },{
                    id:5,
                    title:'数字展区',
                    href:'#sy_box6',
                    img_src:require('../../assets/images/sy/map6.png'),
                    p:'互联网、云计算、大数据、物联网等飞速更新的信息通讯技术正深刻重塑着交通、医疗、农业、金融、通信、社会治理等应用场景。智慧城市的发展和建设，各省市建设智慧产业园，其中成果最为明显的是贵州省，作为首个智慧省事，不断的发展，提高了贵州的经济发展，数字经济成果是全国第一。总的来说，数字建设发展，加快了我国各行业的发展，并取得重大成果。',
                
                }]
        }
    }
}
</script>
<style>
.sy_left_col{
    width: 70%;
    height: 60vh;
    float: left;
  
  }
  .sy_right_col {
    width: 30%;
    height: 60vh;
    margin-top: 6vh;
    float: right;
  }
  .sy_detail {
    margin: 10vh 8vw;
  }
  .sy_detail .title{
    font-size: 4vh;
    margin: 2vh auto;
    text-align: center;
    font-family: STXingkai;
  
  }
  .sy_detail p{
    font-size: 3vh;
    text-align:justify;
    color:rgb(51, 135, 214);
    font-family: STXingkai;
  }
  hr {
    margin: 3vh 0 3vh 0;
    height:1px;
    border:none;
    border-top:1px solid #6ec1e2;
  }
  .sy_detail div {
      text-align: center;
  }

.sy_right_col img{
    margin-top: 5vh;
}


</style>