<template>
    <div class="CN_index">
        <div class="CN_bg1">
            <div class="bg1_bt">
                <h2>数字经济竞争格局</h2>
            </div>
        </div>
        <div class="CN_bg2">
            <div class="bg2_bt">
                <h2>数字经济融合贯通</h2>
            </div>
        </div>
        <div class="CN_bg3">
            <div class="bg3_bt">
                <h2>数字经济隐忧浮现</h2>
            </div>    
        </div>
        <div class="CN_bg4">
            <div class="bg4_header">
                <div class="bg4_bk1">
                    <div class="CN_video">
                        <div class="video_bt" aos="zoom-in">
                        <h2>看“数字经济”</h2>
                        </div>
                            <span>
                                <div class="cn_v01 cn_v wow bounceInRight" @click="VideoVisible1=true"></div>
                                <el-dialog :visible.sync="VideoVisible1">
                                    <video controls="controls" width="100%">
                                        <source src="@/assets/video/china_video1.mp4" type="video/mp4">
                                    </video>
                                    <h3>[第一时间]数博会国际化水平大幅提升大数据加速贵阳经济发展</h3>
                                </el-dialog>
                            </span>
                            <span>
                                <div class="cn_v06 cn_v wow bounceInRight" @click="VideoVisible2=true"></div>
                                <el-dialog :visible.sync="VideoVisible2">
                                    <video controls="controls" width="100%">
                                        <source src="@/assets/video/china_video2.mp4" type="video/mp4">
                                    </video>
                                    <h3>[中国新闻]聚焦中国两会贵州：发展大数据让经济高质量发展</h3>
                                </el-dialog>
                            </span>
                            <span>
                                <div class="cn_v02 cn_v wow bounceInRight" @click="VideoVisible3=true"></div>
                                <el-dialog :visible.sync="VideoVisible3">
                                    <video controls="controls" width="100%">
                                        <source src="@/assets/video/china_video3.mp4" type="video/mp4">
                                    </video>
                                    <h3>[第一时间]聚焦2019贵阳数博会数博会首设扶贫展大数据牵手“农产品”</h3>
                                </el-dialog>
                            </span>
                            <span>
                                <div class="cn_v03 cn_v wow bounceInLeft" @click="VideoVisible4=true"></div>
                                <el-dialog :visible.sync="VideoVisible4">
                                    <video controls="controls" width="100%">
                                        <source src="@/assets/video/china_video4.mp4" type="video/mp4">
                                    </video>
                                    <h3>[贵州新闻联播]大数据与实体经济深度融合全国行首站在贵阳启动</h3>
                                </el-dialog>
                            </span>
                            <span>
                                <div class="cn_v04 cn_v wow bounceInLeft" @click="VideoVisible5=true"></div>
                                <el-dialog :visible.sync="VideoVisible5">
                                    <video controls="controls" width="100%">
                                        <source src="@/assets/video/china_video5.mp4" type="video/mp4">
                                    </video>
                                    <h3>[经济信息联播]聚焦2019贵阳数博会贵州：大数据助力乡村经济发展</h3>
                                </el-dialog>
                            </span>
                            <span>
                                <div class="cn_v05 cn_v wow bounceInLeft" @click="VideoVisible6=true"></div>
                                <el-dialog :visible.sync="VideoVisible6">
                                    <video controls="controls" width="100%">
                                        <source src="@/assets/video/china_video6.mp4" type="video/mp4">
                                    </video>
                                    <h3>[视频]贵州：大数据产业推动社会经济发展</h3>
                                </el-dialog>
                            </span>
                    </div>
                </div>
            </div>
            <div class="bg4_footer">
                <div class="CN_yuan">
                    <div class="CN_yuan1"></div>
                    <div class="CN_yuan2"></div>
                </div>
                <div class="bg4_bk2">
                    <div class="footer_left">
                        <a href="/nanjing" style="color:white" target="_blank">
                            <div class="left_ct" aos="fade-up">
                            <h3>南京打造数字经济名城</h3>
                                <p>在前不久落幕的第十五届中国（南京）国际软件产品和信息服务交易博览会
                                以下简称软博会）上，来自全球30多个国家和地区的1200多家企业齐聚
                                古都南京，共同展望“数字经济”下的“智慧未来”，共签约项目80余项，总投资额超过340亿元。
                                </p>
                            </div>
                            <div class="left_img" aos="fade-up">
                                <p>见证了南京软件产业从起步到腾飞的南京软博会，十四年来，其规模由小到大，参展企业越来越多，
                                    由着重服务外包发展成引领新经济前沿，现已成为南京“新经济”发展的风向标。软博会在留下累累
                                    硕果的同时，也给全体南京市民留下深深思索：即将迈过5000亿元规模门槛的南京软件业，如何在
                                    新一轮发展大潮中抢抓机遇，破解增长速度不够快、龙头企业不够多的难题？同时，如何借力软件
                                    产业，进一步迈向“数字经济名城”？（来源：学习强国）</p>
                            <div class="nanjing_img"></div>
                            </div>
                        </a>
                    </div>
                </div>
                <div class="bg4_bk3">
                    <div class="footer_right">
                        <a href="#" style="color:white" target="_blank">
                            <div class="right_ct" aos="fade-up">
                                <h3>数字经济将重塑中国制造</h3>
                                <p>吸尘器车间经智能化改造后实现“关灯作业”，传统钣金制造在数字化平台辅助
                                    下，生产效率提高三成；无人驾驶汽车依托物联网传感技术，完成了变道、超
                                    车、减速等系列操作……记者近期在我国东部城市采访发现，数字经济的异军突起，正深度重构中国制造。
                                </p>
                            </div>
                            <div class="right_img" aos="fade-up">
                                <p>在新一轮科技革命和产业变革蓄势待发时期，我国数字经济规模持续扩大。根据
                                    中国信息通信产业研究院发布的《中国数字经济发展与就业白皮书（2019年）》
                                    显示，2018年中国数字经济规模达到31.3万亿元，占GDP比重为34.8%。（来源：学习强国）</p>
                                <div class="zhizao_img"></div>
                            </div>
                            </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    head:{
        script:[
            {src:'js/jquery.1.7.1.min.js'},
            {src:'js/aos.js'},
        ],
        link: [
            { rel: 'stylesheet', href: 'css/normalize.css' },
            { rel: 'stylesheet', href: 'css/demo.css' },
            { rel: 'stylesheet', href: 'js/aos.css' },
            { rel: 'stylesheet', href: 'css/styles.css' }
        ]
    },
    data(){
        return{
            VideoVisible1: false,VideoVisible2: false,
            VideoVisible3: false,VideoVisible4: false,
            VideoVisible5: false,VideoVisible6: false
        }
    },
    mounted() {
        AOS.init({
            easing: 'ease-out-back',
            duration: 1000
        });
    }
}
</script>

<style>
    @import "@/assets/css/digital_china.css";
/*数字经济竞争格局样式开始 start*/
.CN_bg1{
    width: 100%;
    height: auto;
}

.CN_bg1 .bg1_bt h2{
    position: absolute;
    left: 40vw;
    top:5vh;
    line-height:5vh;
    font-size: 5vh;
    color: rgb(48, 189, 245);
}

.CN_bg1 .bg1_bt h2:hover{
    animation: bg1_bt 1s linear 3;
}

 @keyframes bg1_bt{
    33.3%{
        font-size: 4vh;
    }
    66.6%{
        font-size: 4.5vh;
    }
    99.9%{
        font-size: 4vh;
    }
}

/*数字经济竞争格局样式结束 end*/


/*数字经济融合贯通样式开始 start*/

.CN_bg2{
    width: 100%;
    height: auto;
}

.CN_bg2 .bg2_bt h2{
    position: absolute;
    left: 40vw;
    top:5vh;
    line-height:5vh;
    font-size: 5vh;
    color: rgb(48, 189, 245);
}

.CN_bg2 .bg2_bt h2:hover{
    animation: bg2_bt 1s linear 3;
}

 @keyframes bg2_bt{
    33.3%{
        font-size: 4vh;
    }
    66.6%{
        font-size: 4.5vh;
    }
    99.9%{
        font-size: 4vh;
    }
}


/*数字经济融合贯通样式结束 end*/


/*数字经济隐忧浮现样式开始 start*/

.CN_bg3{
    width: 100%;
    height: auto;
}

.CN_bg3 .bg3_bt h2{
    width: 100%;
    position: absolute;
    left: 40vw;
    top:5vh;
    line-height:5vh;
    font-size: 5vh;
    color: rgb(48, 189, 245);
}

.CN_bg3 .bg3_bt h2:hover{
    animation: bg3_bt 1s linear 3;
}

 @keyframes bg3_bt{
    33.3%{
        font-size: 4vh;
    }
    66.6%{
        font-size: 4.5vh;
    }
    99.9%{
        font-size: 4vh;
    }
}

/*数字经济隐忧浮现样式结束 end*/


</style>