<template>
    <div class="ysblock">
        <el-carousel :interval="5000" arrow="always" height="60vh"  aos="zoom-in-up">
            <el-carousel-item v-for="(item,idx) in items" :key="idx">
                <el-row>
                <el-col class="left_col_ys">
                    <div class="detail_ys">
                        <div class="titleheader_ys"><a style="color: rgb(48, 189, 245);" :href="item.href">{{item.title}}</a></div>
                        <p>{{ item.p }}</p>
                        <hr class="hr_ys" />
                            <div>
                                <a :href="item.href" style="font-family: STXingkai;font-size:2.5vh;color: rgb(48, 189, 245);">View content>></a>
                            </div>
                    </div>   
                </el-col>
                <el-col class="right_col_ys">
                    <a :href="item.href"><img :src="item.img_src" class="" height="90%" width="90%" style=" border-radius: 50vh"></a>
                </el-col>
            </el-row>
            </el-carousel-item>
        </el-carousel>
    </div>
</template>

<script>
// import animated from 'animate.css' 
export default {
    data(){
        return{
            items: [{
                id:0,
                title:'Big Data College',
                href:'#ebox1_ys',
                img_src: require('../../assets/images/ysblock/img3_js.jpg'),
                p:'Yulin Normal University Big Data College and Big Data Application Innovation Center were unveiled on July 15, 2017. They were established on the basis of the data China "100 Schools Project" innovation project initiated by the School Planning and Construction Development Center of the Ministry of Education and Dawning Information Industry Co., Ltd. Yulin Teachers College is the first experimental Institute of "100 Schools Project" in China, which was determined by the Ministry of Education. It is also the only experimental Institute in southeastern Guangxi.',
            },{
                id:1,
                title:'development history',
                href:'#ebox2_ys',
                img_src: require('../../assets/images/ysblock/img6_zj.jpg'),
                p:'After three years of development, the Data College of Yulin Normal University has made proud achievements and continues to develop at a rapid pace. In August 2016, it became the first pilot cooperative University of data Chinas "100-School Project" innovation project, recognized as the innovation base of "100-School Project" project, and became an important node of "collaborative innovation network of big data application". ',
                
            },{
                id:2,
                title:'Construction achievements',
                href:'#ebox3_ys',
                img_src: require('../../assets/images/ysblock/img3_xq.jpg'),
                p:'Talents: Computer Science and Technology (Big Data Application and Analysis) enrolled 89 students in 2016 and 94 students in 2017. The direction of big data technology focuses on training applied talents in software development, data mining, analysis and application of algorithms, construction and maintenance of distributed system platforms, etc. Hardware: The big data base covers an area of 1200 square meters, and it has the functions of exhibition hall, multimedia computer room, project training room and teachers scientific research team studio.',
                
            },{
                id:3,
                title:'News information',
                href:'#ebox4_ys',
                img_src: require('../../assets/images/ysblock/ys4.png'),
                p:'As the key construction object of the university, Big Data College has attracted wide attention from the society. By deepening the integration of industry and education, deepening cooperation between schools and enterprises, transforming the talent training mode, and adopting the concept of VIP project teaching developed by dawn, students learning plan, purpose and initiative can be improved. In construction, equipment, technology, talent and other aspects have made proud achievements.',
     
            },{
                id:4,
                title:'Student elegance',
                href:'#ebox5_ys',
                img_src: require('../../assets/images/ysblock/img4_scope_5.webp'),
                p:'Big Data College makes overall requirements for talent training standards in three dimensions: knowledge, ability and quality, so as to enable students to master the necessary basic knowledge and meet the characteristics of "wide caliber and thick foundation" undergraduate teaching and training, and to enable students to have the technical application ability of big data engineering specialty and the practical ability needed in their jobs. Requirements for strength and technical skills. ',
                
            }]
        }
    }
    

}
</script>

<style>
.left_col_ys{
    width: 70%;
    height: 60vh;
    float: left;
  
  }
.right_col_ys {
    width: 30%;
    height: 40vh;
    float: right;
    margin-top: 5vh;
    /* border: 1px solid red; */
    margin-top: 10vh;
    filter: brightness(60%);
   
  }
.right_col_ys img {
        transition: all 500ms linear;
}
.right_col_ys img:hover {
    transform: scale(1.1,1.1)
}


.detail_ys {
    margin: 10vh 8vw;
  }
/* .detail_ys .title_ys{
    font-size: 4vh;
    margin: 2vh auto;
} */
.detail_ys p{
font-size: 2.5vh;
text-align: justify;
color: rgb(48, 189, 245);
line-height: 4.5vh;
text-indent: 2em;
}
.hr_ys {
margin: 3vh 0 3vh 0;
height:1px;
border:none;
border-top:1px solid #6ec1e2;
}
.detail_ys div {
    text-align: center;
}
.titleheader_ys {
    text-align: center;
    font-size: 4vh;
    margin: 2vh auto;
    line-height: 6vh;
}
</style>