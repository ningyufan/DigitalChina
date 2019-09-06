<template>
    <div class="gx_box1">
        <div class="tab" aos = "zoom-in">
				智慧城市
			</div>
			<div class="con"  aos = "zoom-in">
				<div class="pic_style" @click="gx_dialog1 = true">
					<div class="img1"><img src="../../assets/images/gx/gxmap.png"  height="100%" width="100%" alt=""></div>
					<div class="img2"><img src="../../assets/images/gx/gxmap1.png"  height="100%" width="100%" alt=""></div>
				</div>
				<div class="cspic_list">
					<div class="cspic_list1"  @click="gx_dialog2 = true">
						<div class="img1"><img src="../../assets/images/gx/nanning.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/nanning1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list2" @click="gx_dialog3 = true">
						<div class="img1"><img src="../../assets/images/gx/liuzhou.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/liuzhou1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list3" @click="gx_dialog4 = true">
						<div class="img1"><img src="../../assets/images/gx/guilin.png"  height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/guilin1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list4" @click="gx_dialog5 = true">
						<div class="img1"><img src="../../assets/images/gx/guigang.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/guigang1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list5" @click="gx_dialog6 = true">
						<div class="img1"><img src="../../assets/images/gx/qinzhou.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/qinzhou1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list6" @click="gx_dialog7 = true">
						<div class="img1"><img src="../../assets/images/gx/yulin.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/yulin1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list7" @click="gx_dialog8 = true">
						<div class="img1"><img src="../../assets/images/gx/yufengqu.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/yufengqu1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list8" @click="gx_dialog9 = true">
						<div class="img1"><img src="../../assets/images/gx/luzhaixian.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/luzhaixian1.png" height="100%" width="100%" alt=""></div>
					</div>
				</div>
            </div>
            <el-dialog :visible.sync="gx_dialog1" width="60%">
                <template slot="title">
                    <div class="gx_diatitle">
                        广西国家级智慧城市——六市一区一县
                    </div>
                </template>
                <span>
                    <div class="gxdia_info">
                        <img src="../../assets/images/gx/gxmap.png"  alt="">
                        <p>
                            国家住房城乡建设部和科学技术部联合公布了第三批国家智慧城市试点名单。钦州、玉林两市成为国家智慧城市新增试点，鹿寨县成为扩大范围试点，被纳入柳州试点。至此，广西累计有6市1区1县入选国家智慧城市试点。
                        </p>
                    </div>                    
                </span>
                <span slot="footer" class="dialog-footer">                    
                    <el-button type="primary" @click="gx_dialog1 = false">返回</el-button>
                </span>
            </el-dialog>
            <el-dialog :visible.sync="gx_dialog2" width="60%">
                <template slot="title">
                    <div class="gx_diatitle">
                       南宁——平安绿城，活力南宁
                    </div>
                </template>
                <span>
                    <div class="gxdia_info">
                        <img src="../../assets/images/gx/nanning.png"  alt="">
                        <p>
                            以“平安”为核心，在市政配套、应急处置、交通能源、人居环境等方面使居民生活达到舒适、便捷、安全的要求，加快推进面向东盟的区域性信息交流中心建设，广泛运用物联网、云计算等新一代信息技术，构建城市运营的智慧环境和全新的城市形态。
                        </p><br/>
                        <p>
                            围绕“平安”二字，以智慧安全和智慧应急为建设重点，通过平台融合、部门协调等，构建全面的应急预警、处警统一平台。具体而言，是通过城市应急联动中心110、119、120、122四个平台，对公安、交通、消防等进行整合，同时通过与城市管理、急救和与市民生活息息相关的水电煤气等单位实现信息整合和共享，提高突发公共事件快速响应和反应能力。同时，结合“绿城”的“绿”通过智慧化的应用，让市民今后生活在更加宜居的生态环境中。
                        </p><br/>
                        <p>
                            在创建期内，南宁市将按照“保障体系与基础设施”、“智慧建设与宜居”、“智慧管理与服务”、“创新项目”等4个类别，计划开展“一个平台、一个中心、四个库和十大工程（建管、节能、绿色建筑、水务、燃气、地下管线及管理、交通、环保、安全与应急）”建设，总投资预计约523亿元。
                        </p><br/>
                        <p>
                            预期到2017年，初步建成覆盖中心城区的智能信息基础设施，居民生活更加安全、便捷、高效、绿色，最终达到构建“平安绿城，活力南宁”的目标。
                        </p><br/>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">                    
                    <el-button type="primary" @click="gx_dialog2 = false">返回</el-button>
                </span>
            </el-dialog>
            <el-dialog :visible.sync="gx_dialog3" width="60%">
                <template slot="title">
                    <div class="gx_diatitle">
                        柳州市
                    </div>
                </template>
                <span>
                    <div class="gxdia_info">
                        <img src="../../assets/images/gx/liuzhou.png" alt="">
                        <p>
                            充分发挥工业优势与资源，建立统一开发的公共信息平台和信息资源共享服务体系。实现城市节约、智能、绿色、低碳的发展目标。
                        </p><br/>
                        <p>
                            在试点阶段时期，柳州市将按照“信息基础设施建设”、“建设与宜居”、“管理与服务”、“创新项目”四个类别，共计划实施24项“智慧城市”建设重点项目，计划总投资约125.6亿元。
                        </p><br/>
                        <p>
                            预期到2018年，基本实现电子政务、电子商务和电子服务等领域较为广泛的智慧应用，打造一批重点示范工程和智慧产业基地，形成“智慧柳州”发展基本框架，创建智慧工业生态宜居城市。
                        </p><br/>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">                    
                    <el-button type="primary" @click="gx_dialog3 = false">返回</el-button>
                </span>
            </el-dialog>
            <el-dialog :visible.sync="gx_dialog4" width="60%">
                <template slot="title">
                    <div class="gx_diatitle">
                        桂林市
                    </div>
                </template>
                <span>
                    <div class="gxdia_info">
                        <img src="../../assets/images/gx/guilin.png" alt="">
                        <p>
                            以“智慧旅游”为智慧城市建设的突破口和信息产业增长点，带动智慧农业、智慧交通等一系列智慧产业发展，逐步完成桂林整体智慧城市的信息化建设。
                        </p><br/>
                        <p>
                            今后几年，桂林市将立足于“创建桂林特色智慧城市”的总体定位，进一步加快网络基础设施建设步伐，促进电信网、计算机网和广电网融合；构建统一的“智慧桂林”电子政务网络，建设桂林云计算中心，完善基础信息数据库，构建地理信息共享平台，建设桂林市信息资源中心；完善信息安全保障体系等。预计到2017年，“智慧桂林”基本框架初步形成，为中西部地区旅游型城市建设智慧城市提供示范经验。
                        </p><br/>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">                    
                    <el-button type="primary" @click="gx_dialog4 = false">返回</el-button>
                </span>
            </el-dialog>
            <el-dialog :visible.sync="gx_dialog5" width="60%">
                <template slot="title">
                    <div class="gx_diatitle">
                        贵港市
                    </div>
                </template>
                <span>
                    <div class="gxdia_info">
                        <img src="../../assets/images/gx/guigang.png" alt="">
                        <p>
                            以“黄金水道、生态宜居”为理念，通过光网城市、无线城市稳步提升网络水平，打造智慧工口、混合交通管控模式等具有一定示范作用的信息化综合应用项目。
                        </p><br/>
                        <p>
                            主要通过公共信息平台、智慧城管、建筑节能、智慧政务、智慧医疗等项目进行试点创建。到2017年，实现网络宽带到村入户，无线网络覆盖中心城区，打造智慧港口、混合交通管控模式等具有一定示范作用的信息化综合应用项目，确保西江流域核心港口地位，促进城市产业升级。到2020年，形成信息高度共享和利用、系统高效协作的“智慧贵港”生态体系。
                        </p><br/>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">                    
                    <el-button type="primary" @click="gx_dialog5 = false">返回</el-button>
                </span>
            </el-dialog>
            <el-dialog :visible.sync="gx_dialog6" width="60%">
                <template slot="title">
                    <div class="gx_diatitle">
                        钦州——打造智慧临港工业城市
                    </div>
                </template>
                <span>
                    <div class="gxdia_info">
                        <img src="../../assets/images/gx/qinzhou.png" alt="">
                        <p>
                            钦州市依托北部湾区域性国际航运物流枢纽和宜商宜居海湾城市的区位优势，以“智慧城管、智慧民生、智慧产业”
                            体系为智慧钦州创建目标，实施智慧港口，智慧园区等一批重点项目。
                        </p><br/>
                        <p>
                            钦州市先后投入了3.5亿元，建成数字城市、地理空间框架、工程项目全生命周期管理信息系统、港口信息系统、
                            社区综治信息管理系统等多个应用系统。其信息技术在港口调度、城市电子政务、数字城市地理空间、社区管理、城市公共安全、
                            城市应急服务、城市交通等方面得到了较为广泛的应用。
                        </p><br/>
                        <p>
                            下一步，钦州市将进一步推进城市管理、建筑节能、地下管线与空间等融合智慧化应用，实现城市的智慧化、现代化、低碳化运行。
                        </p><br/>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">                    
                    <el-button type="primary" @click="gx_dialog6 = false">返回</el-button>
                </span>
            </el-dialog>
            <el-dialog :visible.sync="gx_dialog7" width="60%">
                <template slot="title">
                    <div class="gx_diatitle">
                        玉林——信息化技术的广泛应用
                    </div>
                </template>
                <span>
                    <div class="gxdia_info">
                        <img src="../../assets/images/gx/yulin.png" alt="">
                        <p>
                            玉林市以“建设智慧城市，打造幸福玉林”为智慧城市创建目标，进一步加强数字化城市管理、社区、旅游、交通、医疗、建筑节能、地下管线数字化管理等。
                        </p><br/>
                        <p>
                            目前，玉林市信息化技术在工业、旅游、交通、电子政务、城市管理等各个方面得到广泛应用。其中，数字玉林、天网工程、数字城管系统等多个系统技术先进。
                        </p><br/>
                        <p>
                            未来，玉林市将进一步加强数字化城市管理、社区、交通、医疗、建筑节能、地下管线数字化管理等，以智慧城市创建为契机，推动玉林市城镇化进程。
                        </p><br/>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">                    
                    <el-button type="primary" @click="gx_dialog7 = false">返回</el-button>
                </span>
            </el-dialog>
            <el-dialog :visible.sync="gx_dialog8" width="60%">
                <template slot="title">
                    <div class="gx_diatitle">
                        柳州鱼峰区
                    </div>
                </template>
                <span>
                    <div class="gxdia_info">
                        <img src="../../assets/images/gx/yufengqu.png" alt="">
                        <p>
                            将信息化、工业化、城市化高度融合，以提升物联网和互联网应用水平、政府决策水平和公共信息服务水平。
                        </p><br/>
                        <p>
                            结合柳州智慧城市试点创建，将城区现有各种信息资源进行统一规划、整合，以民生优先、提升城市生活品质为重点，进行城市环境宜居数字化、城市安全防控数字化、城市生活便捷数字化等建设。
                        </p><br/>
                        <p>
                            预计到2016年，依托推进物联网、虚拟集群、三网融合等新技术的广泛应用，初步构建“体系完整、服务到位、管理完善、应用深入、安全保密、基础健全”的“智慧鱼峰”信息化体系。
                        </p><br/>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">                    
                    <el-button type="primary" @click="gx_dialog8 = false">返回</el-button>
                </span>
            </el-dialog>
            <el-dialog :visible.sync="gx_dialog9" width="60%">
                <template slot="title">
                    <div class="gx_diatitle">
                        柳州市鹿寨县——产业智能化的工业强县
                    </div>
                </template>
                <span>
                    <div class="gxdia_info">
                        <img src="../../assets/images/gx/luzhaixian.png" alt="">
                        <p>
                            作为柳州城乡一体化卫星城的鹿寨县，突出“广西工业强县”和“中国生态强县”的特点，在整合原有电子政务、
                            社区网络化管理服务等系统功能基础上建设智慧县城，力争实现促进城镇化与工业化、城镇化与城乡公共服务、
                            城镇化与农业现代化等协调发展目标，推动产业智能化发展和生态文明建设相得益彰。
                        </p><br/>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">                    
                    <el-button type="primary" @click="gx_dialog9 = false">返回</el-button>
                </span>
            </el-dialog>
    </div>
</template>

<script>
export default {
    data() {
        return {
            gx_dialog1: false,
            gx_dialog2: false,
            gx_dialog3: false,
            gx_dialog4: false,
            gx_dialog5: false,
            gx_dialog6: false,
            gx_dialog7: false,
            gx_dialog8: false,
            gx_dialog9: false,

        }
    }

}
</script>

<style>
/* 智慧城市 start */
.gx_box1 {
    width: 100vw;
    height: 60vh;
    background-image: url(../../assets/images/gx/bg1.png);
    background-size: 100% 100%;

}
.gx_box1 .tab {
    width: 100vw;
    height: 15vh;
    line-height: 15vh;
    text-align: center;
    font-size: 6vh;
    font-family: STXingkai;
    color: rgb(48, 189, 245);
    
}
.gx_box1 .tab:hover {
    animation: tab_scale 1s linear 3;
}

@keyframes tab_scale{
    33.3%{
        font-size: 5vh;
    }
    66.6%{
        font-size: 5.5vh;
    }
    99.9%{
        font-size: 5vh;
    }
}


.gx_box1 .con {
    height: 40vh;
    width: 80vw;
    margin: 0 auto;
    position: relative;
}
.gx_box1 .con .pic_style {
    width: 28vw;
    height: 40vh;
    position: absolute;
    left: 0;
    top: 0;
    transform-style: preserve-3d;
    transform: perspective(800px) rotateY(0deg);
}
.gx_box1 .con .pic_style .img1,
.gx_box1 .con .pic_style .img2{
    width: 28vw;
    height: 40vh;
    position: absolute;
    left:0;
    top: 0;
    backface-visibility: hidden;
    transform: perspective(800px) rotateY(0deg);
    transition: all 1s ease;
}
.gx_box1 .con .cspic_list{
    height: 40vh;
    width: 52vw;
    position: absolute;
    right: 0;  
}
.gx_box1 .con .cspic_list .cspic_list1{
    height: 20vh;
    width: 13vw;

    position: relative;
    transform-style: preserve-3d;
    transform: perspective(800px) rotateY(0deg);
}
.gx_box1 .con .cspic_list .cspic_list1 .img1,
.gx_box1 .con .cspic_list .cspic_list1 .img2{
    height: 20vh;
    width: 13vw;

    position: absolute;
    left:0;
    top: 0;
    backface-visibility: hidden;
    transform: perspective(800px) rotateY(0deg);
    transition: all 1s ease;
}
.gx_box1 .con .cspic_list .cspic_list2 .img1,
.gx_box1 .con .cspic_list .cspic_list2 .img2{
    height: 20vh;
    width: 13vw;
    position: absolute;
    left:13vw;
    top: 0;
    backface-visibility: hidden;
    transform: perspective(800px) rotateY(0deg);
    transition: all 1s ease;
}
.gx_box1 .con .cspic_list .cspic_list3 .img1,
.gx_box1 .con .cspic_list .cspic_list3 .img2{
    height: 20vh;
    width: 13vw;
    position: absolute;
    left:26vw;
    top: 0;
    backface-visibility: hidden;
    transform: perspective(800px) rotateY(0deg);
    transition: all 1s ease;
}
.gx_box1 .con .cspic_list .cspic_list4 .img1,
.gx_box1 .con .cspic_list .cspic_list4 .img2{
    height: 20vh;
    width: 13vw;
    position: absolute;
    left:38vw;
    top: 0;
    backface-visibility: hidden;
    transform: perspective(800px) rotateY(0deg);
    transition: all 1s ease;
}
.gx_box1 .con .cspic_list .cspic_list5 .img1,
.gx_box1 .con .cspic_list .cspic_list5 .img2{
    height: 20vh;
    width: 13vw;
    position: absolute;
    left:0vw;
    bottom: 0;
    backface-visibility: hidden;
    transform: perspective(800px) rotateY(0deg);
    transition: all 1s ease;
}
.gx_box1 .con .cspic_list .cspic_list6 .img1,
.gx_box1 .con .cspic_list .cspic_list6 .img2{
    height: 20vh;
    width: 13vw;
    position: absolute;
    left:13vw;
    bottom: 0;
    backface-visibility: hidden;
    transform: perspective(800px) rotateY(0deg);
    transition: all 1s ease;
}
.gx_box1 .con .cspic_list .cspic_list7 .img1,
.gx_box1 .con .cspic_list .cspic_list7 .img2{
    height: 20vh;
    width: 13vw;
    position: absolute;
    left:26vw;
    bottom: 0;
    backface-visibility: hidden;
    transform: perspective(800px) rotateY(0deg);
    transition: all 1s ease;
}
.gx_box1 .con .cspic_list .cspic_list8 .img1,
.gx_box1 .con .cspic_list .cspic_list8 .img2{
    height: 20vh;
    width: 13vw;
    position: absolute;
    left:38vw;
    bottom: 0;
    backface-visibility: hidden;
    transform: perspective(800px) rotateY(0deg);
    transition: all 500ms ease;
}

.gx_box1 .con .cspic_list .cspic_list1 .img2,
.gx_box1 .con .cspic_list .cspic_list2 .img2,
.gx_box1 .con .cspic_list .cspic_list3 .img2,
.gx_box1 .con .cspic_list .cspic_list4 .img2,
.gx_box1 .con .cspic_list .cspic_list5 .img2,
.gx_box1 .con .cspic_list .cspic_list6 .img2,
.gx_box1 .con .cspic_list .cspic_list7 .img2,
.gx_box1 .con .cspic_list .cspic_list8 .img2,
.gx_box1 .con .pic_style .img2 {
    transform: translateZ(2px) rotateY(180deg);
}
.gx_box1 .con .cspic_list .cspic_list1:hover .img1,
.gx_box1 .con .cspic_list .cspic_list2:hover .img1,
.gx_box1 .con .cspic_list .cspic_list3:hover .img1,
.gx_box1 .con .cspic_list .cspic_list4:hover .img1,
.gx_box1 .con .cspic_list .cspic_list5:hover .img1,
.gx_box1 .con .cspic_list .cspic_list6:hover .img1,
.gx_box1 .con .cspic_list .cspic_list7:hover .img1,
.gx_box1 .con .cspic_list .cspic_list8:hover .img1,
.gx_box1 .con .pic_style:hover .img1{
    transform: perspective(800px) rotateY(180deg)
}
.gx_box1 .con .cspic_list .cspic_list1:hover .img2,
.gx_box1 .con .cspic_list .cspic_list2:hover .img2,
.gx_box1 .con .cspic_list .cspic_list3:hover .img2,
.gx_box1 .con .cspic_list .cspic_list4:hover .img2,
.gx_box1 .con .cspic_list .cspic_list5:hover .img2,
.gx_box1 .con .cspic_list .cspic_list6:hover .img2,
.gx_box1 .con .cspic_list .cspic_list7:hover .img2,
.gx_box1 .con .cspic_list .cspic_list8:hover .img2,
.gx_box1 .con .pic_style:hover .img2 {
    transform: perspective(800px) rotateY(0deg)
}

.gx_diatitle {
    font-size: 4vh;
    line-height: 6vh;
}

.gxdia_info {
    width: 55vw;
    margin: 0 auto;
}

.gxdia_info img{
    height: 30vh;
    width: 25vw;
    margin: 0 15vw 0 15vw;
}
.gxdia_info p {
    font-size: 2.5vh;
    line-height: 3.75vh;
    text-indent: 2rem;
} 
/* 智慧城市 end */
</style>