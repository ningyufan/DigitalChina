<template>
    <div class="sy_header">
       <el-carousel :interval="5000" arrow="always" height="60vh" aos="zoom-in-up">
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
                    title:'Digital China',
                    href:'#sy_box1',
                    img_src: require('../../assets/images/sy/map1.png'),
                    p:'Digital China aims to manage China in terms of sustainable development, agriculture, resources, environment, global change, ecosystem, water and soil circulation system, using remote sensing satellite images as the main technical analysis means.',
                },{
                    id:1,
                    title:'Digital Industry',
                    href:'#sy_box2',
                    img_src: require('../../assets/images/sy/map2.png'),
                    p:'Digital industry refers to the public industry which takes information as the processing object, digital technology as processing means, products of consciousness (broad sense of consciousness) as the result, and intervenes in all fields of society as the market. It has no obvious profit for itself, but can improve the profits of other industries.',
                    
                },{
                    id:2,
                    title:'Digital Dynamics',
                    href:'#sy_box3',
                    img_src: require('../../assets/images/sy/map3.png'),
                    p:'The 2nd China Digital Construction Summit opened in early May this year. The Digital China Construction Summit is a platform for information development policy release, e-government and digital economic development achievements display, theoretical experience and practice exchange of digital China construction. This year is also the first year of 5G, the arrival of 5G has promoted the development of digital China.',
                   
                },{
                    id:3,
                    title:'Digital Characters',
                    href:'#sy_box4',
                    img_src: require('../../assets/images/sy/map4.png'),
                    p:'In the process of digital China’s development, a number of digital leaders emerged, leading the development of digital, and put forward suggestions to promote the development of digital China.',
                    
                },{
                    id:4,
                    title:'5G Era',
                    href:'#sy_box5',
                    img_src: require('../../assets/images/sy/map5.png'),
                    p:'The 5G era is the seventh information revolution and the foundation of the seventh information revolution. 5G, known as the "new engine of digital economy", is not only the foundation of new technologies and industries such as artificial intelligence, Internet of Things, cloud computing, block chains, video social networking, but also the key support for "Made in China 2025" and "Industry 4.0".',
                    
                },{
                    id:5,
                    title:'Digital Exhibition Area',
                    href:'#sy_box6',
                    img_src:require('../../assets/images/sy/map6.png'),
                    p:'Rapidly updated information and communication technologies such as the Internet, cloud computing, big data and the Internet of Things are profoundly reshaping the application scenarios of transportation, medical treatment, agriculture, finance, communication and social governance. With the development and construction of smart cities, all provinces and municipalities have built smart industrial parks. The most obvious achievement is Guizhou Province. As the first smart province, continuous development has improved Guizhou’s economic development, and the digital economic achievements are the first in the country. Generally speaking, the development of digital construction has accelerated the development of various industries in China and achieved significant results.',
                
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
    margin-top: 4vh;
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