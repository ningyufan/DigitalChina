<template>
    <div class="gx_box5">
        <div class="tab" aos = "zoom-in">
            智慧教育
        </div>
        <div class="tab_two" aos = "zoom-in" aos-delay = "300">
            广西百校工程院校
        </div>
        <div class="box5_con">
            <div class="con1" @click="dialog1 = true" aos = "fade-right">
                <img src="../../assets/images/gx/box6_pic1.png" height="100%" width="100%" alt="">
            </div>				
            <div class="con2" aos = "fade-left">
                <div class="tariffCards">
                    <div class="card1"  @click="dialog2 = true">
                        <img src="../../assets/images/gx/box6_pic2.png" alt="Economy">
                        <h3>南宁师范大学</h3>						
                    </div>
                    <div class="card2" @click="dialog3 = true">
                        <img src="../../assets/images/gx/box6_pic3.png" alt="Premium Economy">
                        <h3>广西科技师范学院</h3>						
                    </div>
                    <div class="card3" @click="dialog4 = true">
                        <img src="../../assets/images/gx/box6_pic4.png" alt="Business">
                        <h3>北部湾大学</h3>						
                    </div>
                    <div class="card4" @click="dialog5 = true">
                        <img src="../../assets/images/gx/box6_pic5.png" alt="First" >
                        <h3>玉林师范学院</h3>						
                    </div>
                    <div class="card5" @click="dialog6 = true">
                        <img src="../../assets/images/gx/box6_pic6.png" alt="First">
                        <h3>桂林理工大学南宁分校</h3>
                    </div>
                </div>
            </div>
            <el-dialog
                title="瑞翼教育"
                :visible.sync="dialog1"
                width="60%">
                <span>
                    <video controls loop 
                        lass="fillWidth" 
                        width="100%">
                        <source src="../../assets/video/gx_box6_video1.mp4" type="video/mp4"/>
                        浏览器不支持 video 标签，建议升级浏览器。
                        <source src="../../assets/video/gx_box6_video1.mp4" type="video/webm"/>
                        浏览器不支持 video 标签，建议升级浏览器。
                    </video>
                    <br/>
                    <p>
                        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;数据中国“百校工程”
                        是教育部学校规划建设发展中心与曙光信息产业股份有限公司联合实施的产教融合创新项目。
                    </p><br/>
                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;该项目自2016年5月启动，计划未来3年内，
                        在全国范围遴选百所应用型本科院校，以校企合作的模式，共建百所“曙光瑞翼大数据学院”，
                        百个“大数据应用创新中心”，并联网成“大数据应用协同创新网络”，打造兼具人才培养、
                        科研创新、服务地方经济功能的大数据超级平台。
                    </p><br/>
                </span>
                <span slot="footer" class="dialog-footer">
                    <el-button type="primary" @click="dialog1 = false">返回</el-button>
                </span>
            </el-dialog>
            <el-dialog
                title="南宁师范大学"
                :visible.sync="dialog2"
                width="60%">
                <span>
                    <div class="dialog_pic">
                        <img src="../../assets/images/gx/box6_pic2.png" height="100%" alt="">
                    </div>
                    <div class="dialog_info">
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            南宁师范大学（Nanning Normal University），简称“南宁师大”，坐落于广西壮族自治区首府南宁市，
                            入选国家中西部高校基础能力建设工程（二期）、新工科研究与实践项目，为全国深化创新创业教育改革示范高校、
                            教育部数据中国“百校工程”项目试点高校、西南大学对口支援建设院校、广西新增博士学位授予单位立项建设单位、
                            广西一流学科建设高校，对口支援广西民族师范学院。
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;学校办学1953年创办的广西中等学校进修学院和1905年创办的南宁道师范学堂，
                            2002年12月，广西师范学院同广西南宁民族师范学校合并，组建新的广西师范学院。2018年12月，
                            学校正式更名为南宁师范大学。
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            根据2019年3月学校官网信息显示，学校有明秀、长岗、五合、武鸣4个校区，占地面积共3476.68亩，图书馆藏书201.4万册，
                            合作举办1所独立学院；设有22个教学学院，6个教辅单位，有普通本科专业66个；有专任教师1018人，
                            全日制普通本科生16690人，硕士研究生1466人，专科生422人。
                        </p>
                    </div>
                    
                </span>
                <span slot="footer" class="dialog-footer">
                    <el-button type="primary" @click="dialog2 = false">返回</el-button>
                </span>
            </el-dialog>
            <el-dialog
                title="广西科技师范学院"
                :visible.sync="dialog3"
                width="60%">
                <span>
                    <div class="dialog_pic">
                        <img src="../../assets/images/gx/box6_pic3.png" height="100%" alt="">
                    </div>
                    <div class="dialog_info">
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;广西科技师范学院位于广西壮族自治区来宾市，
                            为广西壮族自治区区属公办高等本科院校，是教育部数据中国“百校工程”首批试点高校，
                            广西新建本科学校整体转型发展试点学校，为广西科技厅和来宾市人民政府共建学校。								
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            学院可追溯至创办于1958年的宜山师范专科学校，1970年，在柳州民族农业技术学校基础上组建柳州地区师范学校。
                            2015年升格为广西科技师范学院。2016年入选教育部数据中国“百校工程”项目首批先试先行院校。
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            截至2017年9月，学院占地面积共1617.1亩，其中主校区来宾校区1010.1亩、柳州校区607亩；有13个二级学院，
                            59个专业，其中本科专业16个；有教职工862人，全日制在校生12600多人，来自美国、韩国、泰国、
                            越南等国家的留学生58人。
                        </p>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">
                    <el-button type="primary" @click="dialog3 = false">返回</el-button>
                </span>
            </el-dialog>
            <el-dialog
                title="北部湾大学"
                :visible.sync="dialog4"
                width="60%">
                <span>
                    <div class="dialog_pic">
                        <img src="../../assets/images/gx/box6_pic4.png" height="100%" alt="">
                    </div>
                    <div class="dialog_info">
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;北部湾大学位于广西壮族自治区钦州市，
                            是一所以工学、理学、管理学为主的全日制普通高等学校，是广西壮族自治区人民政府与国家海洋局共建高校、教育部数据中国“百校工程”首批试点高校，
                            国家“十三五”规划建设的“应用型本科高校”项目单位、教育部学校规划建设发展中心“产教融合创新实验项目”基地院校、
                            广西新建本科院校整体转型发展试点院校、全国应用技术大学联盟首批理事高校，学校校园为3A级景区。								
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;学校前身为始建于1973年的钦州地区师范学校。1982年设立钦州地区教师进修学院，
                            1985年增设广西师范学院钦州分院。1988年钦州地区教师进修学院更名为钦州地区教育学院，1991年改建为钦州师范高等专科学校。
                            2004年，创建于1906年的钦州民族师范学校（含广西广播电视大学钦州分校）并入钦州师范高等专科学校。2006年，升格为钦州学院。
                            2018年11月底，教育部批准在钦州学院基础上设立北部湾大学。
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            截至2019年5月，学校占地面积2070亩；设有18个教学单位，开办50个本科专业，有3个硕士学位授权点；共有教职工1200多人
                            （其中专任教师800多人）、全日制在校生14000多人。
                        </p>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">
                    <el-button type="primary" @click="dialog4 = false">返回</el-button>
                </span>
            </el-dialog>
            <el-dialog
                title="玉林师范学院"
                :visible.sync="dialog5"
                width="60%">
                <span>
                    <div class="dialog_pic">
                        <img src="../../assets/images/gx/box6_pic5.png" height="100%" alt="">
                    </div>
                    <div class="dialog_info">
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;玉林师范学院（Yulin Normal University）位于中国优秀旅游城市、
                            广西东南部的玉林市，是广西壮族自治区直属全日制普通本科高校，是广西4所高等教育综合改革试点高校之一。
                            2016年，入选教育部数据中国“百校工程”合作院校。		
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;学校的前身是1945年创办的广西省鬰林师范学校，
                            1952年，改名玉林师范学校。1958年，升格为广西玉林专区师范专科学校。
                            1978年，经国务院批准恢复玉林师范专科学校。1994年，更名为玉林师范高等专科学校。
                            2000年，经教育部批准，玉林师范高等专科学校、玉林市教育学院、玉林市高等职业技术学院、
                            广西广播电视大学玉林分校，合并升格为玉林师范学院。
                            2015年，被确定为广西4所高等教育综合改革试点高校之一。					
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;截至2019年6月，学校占地面积1746亩。学校设有16个二级学院，
                            涵盖了经济学、法学、教育学、文学、历史学、理学、工学、管理学、农学、艺术学等10大学科门类，
                            有63个普通本科专业。现有教职工1330人，专任教师1002人，具有博士、硕士学位教师806人。
                            学校现有全日制在校生18550人，共培养外国留学生人数近1100人。
                        </p>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">
                    <el-button type="primary" @click="dialog5 = false">返回</el-button>
                </span>
            </el-dialog>
            <el-dialog
                title="桂林理工大学南宁分校"
                :visible.sync="dialog6"
                width="60%">
                <span>
                    <div class="dialog_pic">
                        <img src="../../assets/images/gx/box6_pic6.png" height="100%" alt="">
                    </div>
                    <div class="dialog_info">							
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            桂林理工大学南宁分校（Guilin University of Technology AT Nanning）
                            是桂林理工大学的分校，主要承担应用型本科教育与专科教育。
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            2017年12月，教育部学校规划建设发展中心组织专家对申报院校进行了集中审核，
                            按照“院校申报、企业对接、方案优化”的基本原则，综合考量专家组意见，统筹考虑地域分布、
                            学校类型及专业领域等维度，最终遴选桂林理工大学南宁分校为广西区第五个数据中国“百校工程”建设院校。
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            桂林理工大学南宁分校的前身是1985年建校的南宁有色金属工业学校。
                            2000年，南宁分校经广西壮族自治区教育厅批准整体并入桂林理工大学，成为桂林理工大学重要的有机组成部分。
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            截至2018年7月，分校在南宁安吉、空港两个校区，校园面积1300多亩，建筑总面积超过30万平方米；设有6个系，
                            开19个本科专业及41个高职专科专业；有教师近500人，全日制在校生近12000人。
                        </p>							
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">
                    <el-button type="primary" @click="dialog6 = false">返回</el-button>
                </span>
            </el-dialog>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {  
			dialog1: false,
			dialog2: false,
			dialog3: false,
			dialog4: false,
			dialog5: false,
			dialog6: false,
        }
    }
}
</script>

<style>
.gx_box5 {
    width: 100vw;
    height: 100vh;
    background-image: url(../../assets/images/gx/bg6.jpg);
    background-size: 100% 100%; 
    position: relative;
}
.gx_box5 .tab {
    width: 100vw;
    height: 15vh;
    line-height: 15vh;
    text-align: center;
    font-size: 6vh;
    font-family: STXingkai;
    color: rgb(48, 189, 245);
}
.gx_box5 .tab_two {
    width: 100vw;
    height: 6vh;
    line-height: 6vh;
    text-align: center;
    font-size: 4vh;
    font-family: STXingkai;
    color: rgb(48, 189, 245);
}
.gx_box5 .tab:hover {
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

.gx_box5 .box5_con {
    height: 70vh;
    width: 80vw;
    margin: 0 auto 0;
    position: relative;
    /* background-color:rgba(48, 189, 245, 0.6) */
}
.gx_box5 .box5_con .con1{
    height: 60vh ;
    width: 30vw;
    position: absolute;
    left: 2vw;
    top: 5vh;
    background-color: #8063E1;
    background-image: linear-gradient(135deg, #BD7BE8, #8063E1);
    box-shadow: 20px 20px 60px rgba(34, 50, 84, 0.5), 1px 1px 0px 1px #8063E1;
    border-radius: 20px;
    transform-style: preserve-3d;
    transform: perspective(800px) rotateY(30deg);
    transition: all 1s ease;
}
.gx_box5 .box5_con .con1:hover {
    transform: perspective(800px) rotateY(0deg);
    background-image: linear-gradient(60deg, rgba(255, 255, 255, 0) 20%, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0) 80%);
    transform: scale(0.8, 0.8);
}
.gx_box5 .box5_con .con1:after {
    position: absolute;
    top: -70px;
    left: 0;
    content: "";
    width: 200%;
    height: 200%;
  }
.gx_box5 .box5_con .con2{
    height: 70vh ;
    width: 45vw;
    position: absolute;
    left:35vw;
    top: 0;
}

.tariffCards {
    height: 60vh ;
    /* width: 45vw; */
    position: absolute;
    top: 50%;
    left: 50%;
    margin: -27vh 0 0 -11.2vw;
    user-select: none;
    transform: translate3d(0, 0, 0);
    transform-style: preserve-3d;
  }
  .tariffCards:after {
    position: absolute;
    bottom: -27px;
    left: 5%;
    content: "";
    width: 65%;
    height: 30px;
    border-radius: 100%;
    background-image: radial-gradient(rgba(34, 50, 84, 0.04), rgba(34, 50, 84, 0));
  }
  .tariffCards > div {
    position: relative;
    width: 22vw;
    height: 19vh;
    border-radius: 12px;
    color: white;
    transform: rotateX(45deg) rotateY(-15deg) rotate(45deg);
    transition: all 0.4s ease;
    overflow: hidden;
    /* cursor: pointer; */
  }
  .tariffCards > div:after {
    position: absolute;
    top: -70px;
    left: 0;
    content: "";
    width: 200%;
    height: 200%;
    background-image: linear-gradient(60deg, rgba(255, 255, 255, 0) 20%, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0) 80%);
    transform: translateX(-100%);
  }
  .tariffCards > div img {
    height: 13vh;
    width: 13vh;
    margin-top: 2vh;
    margin-left: 1vw;
    pointer-events: none;
  }
  .tariffCards > div h3 {
    position: absolute;
    bottom: 2vh;
    left: 1vw;
    font-size: 18px;
    font-weight: 800;
  }

  .tariffCards > div.card1 {
    margin-top: 0;
    z-index: 4;
    background-color: #8063E1;
    background-image: linear-gradient(135deg, #BD7BE8, #8063E1);
    box-shadow: 20px 20px 60px rgba(34, 50, 84, 0.5), 1px 1px 0px 1px #8063E1;
  }
  .tariffCards > div.card2 {
    margin-top: -70px;
    z-index: 3;
    background-color: #3F58E3;
    background-image: linear-gradient(135deg, #7F94FC, #3F58E3);
    box-shadow: 20px 20px 60px rgba(34, 50, 84, 0.5), 1px 1px 0px 1px #3F58E3;
  }
  .tariffCards > div.card3 {
    margin-top: -70px;
    z-index: 2;
    background-color: #2C6FD1;
    background-image: linear-gradient(135deg, #21BBFE, #2C6FD1);
    box-shadow: 20px 20px 60px rgba(34, 50, 84, 0.5), 1px 1px 0px 1px #2C6FD1;
  }
  .tariffCards > div.card4 {
    margin-top: -70px;
    z-index: 1;
    background-color: #352F64;
    background-image: linear-gradient(135deg, #415197, #352F64);
    box-shadow: 5px 5px 60px rgba(34, 50, 84, 0.1), 1px 1px 0px 1px #352F64;
  }
  .tariffCards > div.card5 {
    margin-top: -70px;
    background-color: #352F64;
    background-image: linear-gradient(135deg, #081964, #352F64);
    box-shadow: 5px 5px 60px rgba(34, 50, 84, 0.1), 1px 1px 0px 1px #352F64;
  }
  .tariffCards > div:hover {
    transform: rotateX(30deg) rotateY(-15deg) rotate(30deg) translate(-25px, 50px);
  }
  .tariffCards > div:hover:after {
    transform: translateX(100%);
    transition: all 1.2s ease-in-out;
  }
  .gx_box5 .box5_con .dialog_pic {
      height: 30vh;
      width: 100%;
      text-align: center;
      /* background-color: #21BBFE; */
  }

</style>