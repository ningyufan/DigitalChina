<template>
    <div class="cn_header">
       <el-carousel :interval="5000" arrow="always" height="60vh"  aos="zoom-in-up">
            <el-carousel-item v-for="(item,idx) in items" :key="idx">
                <el-row>
                <el-col class="cn_left_col">
                    <div class="cn_detail">
                        <p class="title"><a style="color: rgb(48, 189, 245);" :href="item.href">{{item.title}}</a></p>
                        <p>{{ item.p }}</p>
                        <hr class="hr" />
                            <div>
                                <a :href="item.href" style="font-size:2.5vh;font-family: STXingkai;line-height: 3.75vh;color: rgb(48, 189, 245);">View content>></a>
                            </div>
                    </div>   
                </el-col>
                <el-col class="cn_right_col">
                    <a :href="item.href"><img :src="item.img_src" height="60%" width="70%" alt="" style="border-radius:100%;"></a>
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
                    title:'Opportunities and Challenges',
                    href:'#cnbg1',
                    img_src: require('../../assets/images/dchina/tz.jpg'),
                    p:'The rise of China’s digital economy is like a bamboo shoot: China accounts for 42% of global e-commerce; one third of the world’s most successful technology start-ups are in China; and China’s annual total mobile payment is 11 times that of the United States. The rapid development of China’s digital economy is attributed to its rich and diverse innovation and entrepreneurship ecosystem, the friendly attitude of regulators and government to technological development, and the huge consumer market. China has 731 million Internet users, more than the EU and the United States combined...',
                },{
                    id:1,
                    title:'Promoting New Development',
                    href:'#cnbg2',
                    img_src: require('../../assets/images/dchina/szjj1.png'),
                    p:'In the new round of scientific and technological revolution and industrial transformation, the scale of China’s digital economy continues to expand. According to the White Paper on China’s Digital Economic Development and Employment (2019) published by China Information and Communication Industry Research Institute, the scale of China’s digital economy reached 31.3 trillion yuan in 2018, accounting for 34.8% of GDP.',
                    
                },{
                    id:2,
                    title:'Promoting Urban Development',
                    href:'#cnbg3',
                    img_src: require('../../assets/images/dchina/szjj9.jpg'),
                    p:'Intelligent city is an advanced form of urban informatization, which makes full use of the new generation of information technology in all walks of life in the city based on the next generation innovation (Innovation 2.0) of the knowledge society, and realizes the deep integration of informatization, industrialization and urbanization. It helps to alleviate the "big city disease", improve the quality of urbanization, and realize the refinement and dynamic management of urbanization. To manage and improve the effectiveness of urban management and the quality of life of citizens...',
                   
                },{
                    id:3,
                    title:'Wisdom China',
                    href:'#cnbg4',
                    img_src: require('../../assets/images/dchina/szzg.jpg'),
                    p:'Digital China aims to manage China in terms of sustainable development, agriculture, resources, environment, global change, ecosystem, water and soil circulation system, using remote sensing satellite images as the main technical analysis means. But in the report of the 19th National Congress of the CPC, digital China is a broader concept. It is the scope of China’s national informatization. Broadband China, Internet, big data and cloud computing are all the contents of digital China.',
                    
                },{
                    id:4,
                    title:'Look"Digital Economy"',
                    href:'#cnbg5',
                    img_src: require('../../assets/images/dchina/szjj.jpg'),
                    p:'Focus on the number of expositions, see the development of digital China, see the application of big data in various fields. Big data industry promotes the development of society, continues to promote the new development of the city, builds a smart city, and continues to promote the rapid and stable development of the economy.',
                    
                },{
                    id:5,
                    title:'County Economic Development',
                    href:'#cnbg6',
                    img_src:require('../../assets/images/dchina/cn2.png'),
                    p:'Rapidly updated information and communication technologies such as the Internet, cloud computing, big data and the Internet of Things are profoundly reshaping the application scenarios of transportation, medical treatment, agriculture, finance, communication and social governance. At the same time, with the development of smart city, the development of smart city obviously shows the trend of popularization from large and medium-sized cities to small and medium-sized cities, especially to county areas.',
                
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
    margin-top: 10vh;
    float: right;
  }

.cn_right_col img {
    transition: all 500ms linear;
}
.cn_right_col img:hover {
    transform: scale(1.1,1.1)
}

  .cn_detail {
    margin: 10vh 8vw;
    color: rgb(48, 189, 245);
  }
  .cn_detail .title{
    font-size: 4vh;
    text-align: center;
    line-height: 6vh;
    font-family: STXingkai;
  
  }
.cn_detail a{
    color: rgb(48, 189, 245);
  }

  .cn_detail p{
    font-size: 2.5vh;
    line-height: 3.75vh;
    text-align:justify;
    font-family: STXingkai;
    text-indent: 2em;
    color: rgb(48, 189, 245);
  }
  hr {
    margin: 3vh 0 3vh 0;
    height:1px;
    border:none;
    border-top:1px solid #6ec1e2;
  }
  .cn_detail div {
      text-align: center;
       color: rgb(48, 189, 245);
  }
</style>