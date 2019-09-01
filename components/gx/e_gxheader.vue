<template>
    <div class="DigitalGX">
       <el-carousel :interval="5000" arrow="always" height="60vh">
            <el-carousel-item v-for="(item,idx) in items" :key="idx">
                <el-row>
                <el-col class="left_col">
                    <div class="detail">
                        <p class="title"><a :href="item.href">{{item.title}}</a></p>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{{ item.p }}</p>
                        <hr class="hr" />
                            <div>
                                <a :href="item.href" style="font-size:2vh">View content>></a>
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
                    title:'Smart City',
                    href:'#box1',
                    img_src: require('../../assets/images/gx/h_pic1.png'),
                    p:'Intelligent city is an advanced form of urban informatization, which makes full use of the new generation of information technology in all walks of life in the city based on the next generation innovation (Innovation 2.0) of the knowledge society, and realizes the deep integration of informatization, industrialization and urbanization. It helps to alleviate the "big city disease", improve the quality of urbanization, and realize the refinement and dynamic management of urbanization. To manage and improve the effectiveness of urban management and the quality of life of citizens.',
                },{
                    id:1,
                    title:'Intelligent Tourism',
                    href:'#box3',
                    img_src: require('../../assets/images/gx/h_pic3.png'),
                    p:'Intelligent tourism is also called intelligent tourism. It is to make use of new technologies such as cloud computing and Internet of Things, through the Internet/mobile Internet, with the help of portable terminal Internet devices, actively perceive the information of tourism resources, tourism economy, tourism activities, tourists and so on, timely release, so that people can timely understand these information, timely arrange and adjust work and tourism. Planning, so as to achieve the effect of intelligent perception and convenient use of all kinds of tourism information. The construction and development of intelligent tourism will ultimately be embodied in four levels: tourism experience, tourism management, tourism services and tourism marketing.',
                    
                },{
                    id:2,
                    title:'Wisdom Life',
                    href:'#box4',
                    img_src: require('../../assets/images/gx/h_pic4.png'),
                    p:'Intelligent life refers to the sum of all kinds of life in the process of human existence, generally refers to the meaning of happiness, and life is actually an interpretation of life. Intelligent life platform can freely communicate with mainstream smart home brand products. At any time and on any occasion, home users can freely access the relevant information and have the characteristics of social interaction through wireless links to the Internet.',
                   
                },{
                    id:3,
                    title:'Intelligent agriculture',
                    href:'#box5',
                    img_src: require('../../assets/images/gx/h_pic5.png'),
                    p:'Intelligent agriculture is the specific manifestation of the wisdom economy in agriculture, or the wisdom economy form in agriculture. Intelligent agriculture is an important part of the smart economy. For developing countries, smart agriculture is the main part of the smart economy. It is the main way for developing countries to eliminate poverty, achieve the advantage of backwardness, catch up with economic development and achieve catch-up strategy.',
                    
                },{
                    id:4,
                    title:'Intelligence Education',
                    href:'#box6',
                    img_src: require('../../assets/images/gx/h_pic6.png'),
                    p:'Intelligent education, namely educational informationization, refers to the process of comprehensively and thoroughly using modern information technology to promote educational reform and development in the field of education (education management, education and teaching, and education and scientific research). Its technical characteristics are digitalization, networking, intellectualization and multimedia. Its basic characteristics are openness, sharing, interaction, collaboration and ubiquitous. Promote the modernization of education with educational informationization and change the traditional mode with information technology.',
                    
                },{
                    id:5,
                    title:'Digital Guangxi',
                    href:'#box7',
                    img_src:require('../../assets/images/wuti.png'),
                    p:'Digital Guangxi is an important part of digital city. The Guangxi Basic Geographic Information Center is charged with the task of constructing the geospatial basic framework of "Digital Guangxi". Digital city is based on computer technology, multimedia technology and large-scale storage technology, with broadband network as the link, using remote sensing, global positioning system, geographic information system, telemetry, simulation-virtual technology, to describe the city in multi-resolution, multi-scale, multi-space-time and multi-kinds of three-dimensional, namely, convenience. By means of information technology, the whole contents of the past, present and future of the city can be realized digitally and virtually on the network.',
                
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
  
  }
  .right_col {
    width: 30%;
    height: 60vh;
    float: right;
    margin-top: 5vh;
  }
  .detail {
    margin: 10vh 8vw;
  }
  .detail .title{
    font-size: 4vh;
    text-align: center;
    margin: 2vh auto;
  
  }
  .detail p{
    font-size: 2.5vh;
    text-align: justify;
    color:rgb(51, 135, 214);
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