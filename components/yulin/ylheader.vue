<template>
    <div class="yl_header">
        <el-carousel :interval="5000" arrow="always" height="60vh">
            <el-carousel-item v-for="(item,idx) in items" :key="idx">
                <el-row>
                <el-col class="left_col_yl">
                    <div class="detail_yl">
                        <div class="title_yl" style="font-size: 10vh;"><a :href="item.href">{{item.title}}</a></div>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{{ item.p }}</p>
                        <hr class="hr_yl" />
                            <div>
                                <a :href="item.href" style="font-size:2vh">查看内容>></a>
                            </div>
                    </div>   
                </el-col>
                <el-col class="right_col_yl">
                    <a :href="item.href"><img :src="item.img_src" class="" height="90%" width="90%" style=" border-radius: 50vh"></a>
                </el-col>
            </el-row>
            </el-carousel-item>
        </el-carousel>
    </div>
</template>

<script>
export default {
    data(){
        return{
            items: [{
                id:0,
                title:'智慧城市建设',
                href:'#ebox1_yl',
                img_src: require('../../assets/images/yulin/city_p3.png'),
                p:'智慧城市建设就是运用信息和通信技术手段感测、分析、整合城市运行核心系统的各项关键信息，从而对包括民生、环保、公共安全、城市服务、工商业活动在内的各种需求做出智能响应。其实质是利用先进的信息技术，实现城市智慧式管理和运行，进而为城市中的人创造更美好的生活，促进城市的和谐、可持续成长。',
            },{
                id:1,
                title:'互联网+"政务服务"',
                href:'#ebox2_yl',
                img_src: require('../../assets/images/yulin/zw_p1.jpg'),
                p:'互联网+政务服务”是利用互联网技术将现实政务服务进行结构重组和流程再造，以使其符合“互联网+”思维，并在此基础上以线上“并行”的“数据流”代替线下“串行”的“人流”，来实现政务服务的高效、高质供给,以简政放权、创新监管、提升服务为核心，以政府权力清单为基础，以信息化技术为支撑，创新实践“互联网+”思维，开启从“群众跑腿”到“数据跑腿”的服务管理新模式。',
                
            },{
                id:2,
                title:'智慧旅游建设',
                href:'#ebox3_yl',
                img_src: require('../../assets/images/yulin/travel_p5.png'),
                p:'智慧旅游依托信息技术，主动获取游客信息，形成游客数据积累和分析体系，全面了解游客的需求变化、意见建议以及旅游企业的相关信息，实现科学决策和科学管理。玉林市提出以旅游业为优势产业，通过对区域内经济社会资源尤其是旅游资源、相关产业、生态环境、公共服务、体制机制、政策法规、文明素质等进行全方位、系统化的优化提升，实现区域资源有机整合、产业融合发展、社会共建共享，以旅游业带动和促进经济社会协调发展。'
                
            },{
                id:3,
                title:'大数据助力精准扶贫',
                href:'#ebox4_yl',
                img_src: require('../../assets/images/yulin/fp_p3.jpg'),
                p:'综合运用大数据手段，完善精准脱贫大数据平台建设，动态管理精准扶贫资金项目，保证扶贫资金项目与扶贫对象有效精准对接，实现全过程跟踪的精准扶贫动态管理，促进精准扶贫在各领域内信息资源的汇聚整合和关联应用，做到精确的查缺补漏，避免贫困人口的遗漏、避免扶贫措施的错位,以此实现扶贫工作的精准监控、全过程监控，扶贫到位。',
     
            },{
                id:4,
                title:'大数据扶持特色产业',
                href:'#ebox5_yl',
                img_src: require('../../assets/images/yulin/chanye_p4.jpg'),
                p:'从国内外大数据发展背景、本地现状与基础、发展路径与策略、基础设施建设、行业应用、产业创新、产业生态打造等方面，制定了详细深入的发展规划。玉林市政府对大数据产业的发展模式、商业模式以及相关重大工程给出了详细说明，全面体现实现“规划与计划相结合，继承与创新相结合”的产业发展新模式。',
                
            }]
        }
    }
    

}
</script>

<style>
.left_col_yl{
    width: 70%;
    height: 60vh;
    float: left;
  
  }
.right_col_yl {
    width: 30%;
    height: 40vh;
    float: right;
    margin-top: 5vh;
    /* border: 1px solid red; */
    margin-top: 10vh;
    filter: brightness(60%);
   
  }
.detail_yl {
    margin: 10vh 8vw;
  }
.detail_yl .title_yl{
    font-size: 4vh;
    margin: 2vh auto;
    text-align: center;
}
.detail_yl p{
font-size: 2.5vh;
text-align: justify;
color:rgb(51, 135, 214);
}
.hr_yl {
margin: 3vh 0 3vh 0;
height:1px;
border:none;
border-top:1px solid #6ec1e2;
}
.detail_yl div {
    text-align: center;
}
.titleheader_yl{
    text-align: center;
    font-size:10vh;
    margin: 2vh auto;
}
</style>

