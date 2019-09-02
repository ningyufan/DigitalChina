<template>
    <div class="ysblock">
        <el-carousel :interval="5000" arrow="always" height="60vh"  aos="zoom-in-up">
            <el-carousel-item v-for="(item,idx) in items" :key="idx">
                <el-row>
                <el-col class="left_col_ys">
                    <div class="detail_ys">
                        <div class="titleheader_ys"><a :href="item.href">{{item.title}}</a></div>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{{ item.p }}</p>
                        <hr class="hr_ys" />
                            <div>
                                <a :href="item.href" style="font-size:2.5vh;font-family: STXingkai;">查看内容>></a>
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
                title:'大数据学院',
                href:'#box1_ys',
                img_src: require('../assets/images/ysblock/img3_js.jpg'),
                p:' 玉林师范学院大数据学院、大数据应用创新中心于2017年7月15日揭牌成立,是基于教育部学校规划建设发展中心联合曙光信息产业股份有限公司发起的数据中国“百校工程”产教融合创新项目而设立的。玉林师范学院是首批被教育部确定的数据中国“百校工程”试点院校,也是桂东南地区唯一一所试点院校。',
            },{
                id:1,
                title:'发展历程',
                href:'#box2_ys',
                img_src: require('../assets/images/ysblock/img6_zj.jpg'),
                p:'玉林师范大数据学院历经三年时间的发展，取得了傲人的成绩，并继续以迅猛的速度发展着。2016年8月，成为数据中国“百校工程”产教融合创新项目先行先试合作院校，确认为“百校工程”项目创新基地，成为“大数据应用协同创新网络”的重要节点。2017年7月，玉林师范学院“大数据应用创新中心”“曙光瑞翼大数据学院”正式揭牌成立；8月，玉林市大数据研究院正式成立；11月，市校共建的玉林市大数据研究院举行签约仪式。',
                
            },{
                id:2,
                title:'建设成果',
                href:'#box3_ys',
                img_src: require('../assets/images/ysblock/img3_xq.jpg'),
                p:'人才方面：计算机科学与技术专业（大数据应用与分析方向）于2016年招生89名，2017年招生94名。大数据技术方向侧重于培养软件开发、数据挖掘、算法的分析与应用、分布式系统平台搭建维护等方面的应用型人才。硬件方面：大数据基地占地面积1200平方米，建设有展示厅、多媒体机房、项目实训室、教师科研团队工作室等功能区。',
                
            },{
                id:3,
                title:'新闻动态',
                href:'#box4_ys',
                img_src: require('../assets/images/ysblock/ys4.png'),
                p:'大数据学院作为学校重点建设对象，其一举一动受到了社会的广泛关注。通过深化产教融合，校企深度合作，转变人才培养模式，采用曙光开发的VIP项目化教学的理念，提高学生学习的计划性、目的性和主动性。在建筑、设备、技术、人才等方面都取得了傲人的成绩。',
     
            },{
                id:4,
                title:'学生风采',
                href:'#box5_ys',
                img_src: require('../assets/images/ysblock/img4_scope_5.webp'),
                p:'大数据学院围绕知识、能力、素质三个维度对人才培养标准做整体要求，使学生掌握必要的基础知识，满足“宽口径、厚基础”本科教学培养的特点；使学生具备大数据工程专业技术应用能力，具备工作岗位中所需要的实践能力和技术技能要求。同时，注重培养学生具备创新精神、沟通表达、团队协作及抗压适应等的基本职业素养和基本素质。',
                
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
    /* margin-right: 2%; */
    /* border: 1px solid red; */
    margin-top: 10vh;
    filter: brightness(60%);
   
  }
.detail_ys {
    margin: 10vh 8vw;
  }
/* .detail_ys .title_ys{
    font-size: 4vh;
    margin: 2vh auto;
} */
.detail_ys p{
font-size: 3vh;
text-align: justify;
font-family: STXingkai;
color:rgb(51, 135, 214);
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
.titleheader_ys{
    text-align: center;
    font-size: 4vh;
    margin: 2vh auto;
    font-family: STXingkai;
}
</style>