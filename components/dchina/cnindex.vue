<template>
    <div class="CN_index">
        <div class="CN_bg" id="cnbg1">
            <div class="bg_bt" aos="zoom-in">
                数字经济挑战机遇
            </div>    
            <div class="cn_bg">
                <div class="bg_row1">
                    <div class="cn_rightheader">
                        <div class="right_headerimg1" @click="TZ_Visible=true" aos="fade-right">
                            <span>"数字社会"运行状态的四个特征</span>
                        </div>
                        
                    </div>
                    <div class="cn_leftheader">
                        <div class="left_headerimg1" @click="JZ_Visible=true" aos="fade-left">
                            <span>数字经济影响城市未来竞争格局</span>
                        </div>
                    </div>
                </div>
                <div class="fk" aos="zoom-in"><img src="../../assets/images/dchina/cfk.png" height="100%" alt=""></div>
                <div class="bg_row2">
                    <div class="cn_rightheader" aos="fade-right">
                        <div class="right_headerimg21" @click="JY_Visible=true">
                            <span>共享机遇</span>
                        </div>
                        <div class="right_headerimg22" @click="RH_Visible=true">
                            <span>融合贯通</span>
                        </div>
                    </div>
                    <div class="cn_leftheader" aos="fade-left">
                        <div class="left_headerimg21" @click="YY_Visible=true">
                            <span>隐忧浮现</span>
                        </div>
                        <div class="left_headerimg22" @click="FZ_Visible=true">
                            <span>发展前景</span>
                        </div>
                    </div>
                </div>
                <el-dialog :visible.sync="TZ_Visible" width="50%">
                    <div class="Digital_TZ">
                        <center>
                            <h2>“数字社会”运行状态的四个特征</h2>
                        </center><br/>
                        <div class="TZ_bg"></div><br>
                            <div class="TZ_ct">
                                <p>“数字社会”在其基本架构和整体运行上最为突出的一个特点就是它在数字化转换的前提下，
                                    依托互联网络，从最具有基础性意义的技术保障和运作机制层面，解决人们在社会生活中
                                    所必须要面对的一系列基本问题，得益于数字化、网络化和智能化的助推，建构起了活动
                                    平台和通行路径。“数字社会”和网络生活在运行状态上，显现出以下四个方面的本质特征。
                                </p><br/>
                                <p><b>第一、跨域连接与全时共在:</b>跨域连接首先解决的是普遍连接的问题。普遍连接既包括人与
                                    人之间的数字化连接，也包括智能设备与智能设备等物与物之间的数字化连接，还包括依托
                                    数字化而实现的人、物、智能设备相互之间的连接和贯通。
                                </p><br/>
                                <p><b>第二、行动自主与深入互动:</b>数字社会、网络时代和赛博空间，客观上为作为社会生活之行为
                                        主体的人的行为活动自由，提供了极为便利的基础条件。</p><br/>
                                <p><b>第三、数据共享与资源整合:</b>网络世界贯通的是一个个的人、一台台的电脑和移动终端设备以
                                    及一个个的大型服务器和数据库。在某种意义上讲，网络空间，其实就是一个信息数据不断生
                                    成、存储、流转和分享的特定空间。</p><br/>
                                <p><b>第四、智能操控与高效协作:</b>机械化、自动化和智能化的实现，是科学技术进步带给人类社会生
                                    活的“福利”。</p>
                            </div>
                    </div>
                </el-dialog>
                <el-dialog :visible.sync="JZ_Visible" width="50%">
                    <div class="Digital_JZ">
                        <center>
                            <h2>数字经济影响城市未来竞争格局</h2>
                        </center><br/>
                        <div class="JZ_bg"></div><br>
                            <div class="JZ_ct">
                                <p>古老街区遇上数字中国，将发生怎样的蝶变？作为第二届数字中国建设峰会预热活动，“有福之州·对话未来”
                                    5月5日在福州三坊七巷举行，各界人士齐聚一堂，畅想未来。</p><br/>
                                <p>城市让生活更美好，数字经济让城市更美好。一方面，数字经济有助于城市优化资源配置、创新增
                                    长方式、培育发展新动能；另一方面，大数据、云计算、物联网等信息技术的应用，有助于打破
                                    “信息孤岛”，提升政府决策科学化、城市管理精细化以及公共服务便利化水平，提升人民群众获得
                                    感、幸福感和安全感。
                                </p><br/>
                                <p>以福州为例，2018年福州数字经济规模突破2800亿元，占地区生产总值的36%。在民生领域，国家健
                                    康医疗大数据（福州）服务平台覆盖人群达711万，汇聚数据超200亿条，通过“大数据+医疗”，提升
                                    了基层诊疗水平，有效解决了医疗资源分布不均的问题，实现了“数据多跑路，群众少跑腿”，成为医
                                    疗惠民的有效支撑。
                                </p><br/>
                                <p>国家发展改革委近期公布的《2019年新型城镇化建设重点任务》明确提出，要优化提升新型智慧城市建
                                    设评价工作，指导地级以上城市整合建成数字化城市管理平台，增强城市管理综合统筹能力，提高城市
                                    科学化、精细化、智能化管理水平。</p>
                                <p>数字城市建设为未来城市竞争格局提供了新的观察视角。随着数字经济发展，西部城市也可以与东部城市
                                    站在同一起跑线上。这就要求各地抓住契机，跨越数字鸿沟，通过发展数字经济，加快产业升级步伐。</p><br/>
                                <p>进一步来说，数字城市由谁建？怎么建？数字城市建设需求多样、技术复杂，这需要包括政府、企业、
                                    高校、科研院所等社会各方共同参与，广泛开展联合创新。</p><br/>
                            </div>
                    </div>
                </el-dialog>
                <el-dialog :visible.sync="JY_Visible" width="50%">
                    <div class="Digital_JY">
                        <center>
                            <h2>共享机遇 共谋发展——数博会加速中国大数据产业融合创新</h2></center><br/>
                        <div class="JY_bg"></div><br>
                        <div class="JY_ct">
                            <p>初夏时节，万物葱茏。为期4天的2019中国国际大数据产业博览会在贵阳落下帷幕。作为全球首个
                                大数据主题博览会，数博会已经走过5个年头，每年都促成了一批项目签约，产生了许多前沿思想。
                            </p><br/>
                            <p><b>第一、数字经济增添活力:</b>“我们大力推动大数据与实体经济深度融合，实施‘万企融合’和
                            ‘百企引领’大行动，每年建设100个融合标杆项目、1000个融合示范项目，计划用3到5年时间，带动1万
                            户以上实体经济企业与大数据深度融合，推动传统产业数字化、网络化、智能化转型。”贵州省大数据发
                            展管理局副局长娄松说。
                            </p><br/>
                            <p><b>第二、数据互通共享助力精准扶贫:</b>中国一直是世界减贫事业的积极倡导者和有力推动者。
                            2019年数博会延续此前对脱贫攻坚领域的关注，首次举办了“大数据与全球减贫”高端对话。“我亲眼看
                            到了中国的减贫成效，很了不起。”联合国开发计划署驻华代表处副代表戴文德在高端对话上说。在他
                            看来，中国的减贫成效来之不易，其在运用大数据精准定位贫困人口，精准找到致贫原因并提供解决方
                            案上，对世界减贫具有借鉴意义。</p><br/>
                            <p><b>第三、国际合作“朋友圈”越来越广:</b>纵观每届数博会，参会规模、会议成果等一项项纪录
                            不断被刷新。今年，参展企业达到448家，其中境外参展企业达到156家。5年来，借助数博会，苹果、
                            戴尔等世界500强企业进入中国更多业务领域。印度国家信息技术学院中国区域技术总监升迪说，
                            去年数博会上，中印IT产业集聚区和大数据培训学院正式落户贵阳，印度大数据企业期待以贵州为桥头堡，
                            进入中国发展。在科技领域，尤其是大数据发展方面，没有开放是不行的。”中国科学院院士梅宏认为，
                            在信息时代要构建人类命运共同体，也要构建网络空间命运共同体，在开放中加强联合创新、协同创新，
                            在深化国际合作中实现互利共赢。</p><br/>
                        </div>
                    </div>
                </el-dialog>
                <el-dialog :visible.sync="RH_Visible" width="50%">
                    <div class="Digital_RH">
                        <center>
                            <h2>“大数据”融合贯通 让生活更便捷</h2></center><br/>
                        <div class="RH_bg"></div><br>
                        <div class="RH_ct">
                            <p>2019中国国际大数据产业博览会正在贵阳举行，大数据如何应用成为人们关注的焦点。“大数据”的融合
                                贯通，让分散的数据孤岛被打通，我们的生产、生活正在发生全新的变化。这样就会逐渐实现贵州省
                                提出的进一张网办全省事。目前，贵州省400多个高频和热点的事情都可以在手机上办理，比如说：
                                代开发票、出生医学证明补办等等。如果我开车出门忘带驾驶证也不要紧，刚刚上线的身份证、
                                驾驶证的电子证照，只要打开手机进入移动端点击驾驶证，通过张张嘴点点头和摇摇头，就可以生成
                                这样的电子证照交给交警了。
                            </p><br/>
                            <p>在展览区，大数据的应用随处可见，给我们更直观的感受就是大数据让我们的生活更便捷更智慧。
                                在我旁边的云上贵州数字政务平台上，已经汇聚了贵州省9个市州40多个省直部门9000多个应用融合。
                                目前，利用大数据和人工智能等技术，贵州正在努力尝试让云上贵州数据平台，具备自我学习的能力，变得更加智能。
                            </p><br/>
                            <p>而政府各个部门、以及企业和个人的数据要实现共享和交换，最重要的就是保证安全。在本届数博会上，一套由我国自
                                主研发的“数据交换二维码摆渡系统”正式推出。它利用“模拟人眼识别”和独特的“高速二维码编解码技术”，不但实现内、
                                外网物理隔断，同时兼顾数据传输的安全、高效。</p>
                            
                        </div>
                    </div>
                </el-dialog>
                <el-dialog :visible.sync="YY_Visible" width="50%">
                    <div class="Digital_YY">
                        <center>
                            <h2>“数字经济”发展隐忧浮现</h2></center><br/>
                        <div class="YY_bg"></div><br>
                        <div class="YY_ct">
                            <p>随着大数据在国家治理、经济发展等方面的影响日益加深，数据安全问题逐渐凸显，个人信息泄露、
                                网络诈骗给公民人身和财产安全带来威胁。进入“数字经济”时代，如何给数据安全“上锁”成为2019
                                中国国际大数据产业博览会与会专家讨论的焦点。
                            </p><br/>
                            <p><b>“数字经济”高速发展伴随安全隐忧:</b>中国信通院发布的《中国数字经济发展与就业白皮书（2019年）》
                            显示，近年来我国“数字经济”规模保持快速增长，2018年我国数字经济总量达到31.3万亿元，占GDP比重超过1/3，
                            达到34.8%，占比同比提升1.9个百分点。本届博览会发布的《中国大数据发展报告》显示，当前全球贸易已经有50%
                            以上实现了数字化。数字经济时代，数据的集聚开发应用加大了个人隐私泄露、泄密的风险。此外，大数据本身也在
                            帮助黑客来进行相应的数据分析。
                            </p><br/>
                            <p><b>加快数据分层分级保护:</b>5月28日，国家网信办发布《数据安全管理办法（征求意见稿）》，就维护国家安全、
                            社会公共利益，保护公民、法人和其他组织在网络空间的合法权益，保障个人信息和重要数据安全，征求广大网民意见。
                            继《中华人民共和国网络安全法》颁布实施后，2018年《个人信息保护法》被列入五年立法规划，2019年《中华人民共和国数据安全法》
                            被列入年度立法规划。</p><br/>
                            <p><b>全面提升数据安全保障能力:</b>与会专家指出，应建立管理、技术、运营、监管四个维度，平台、数据、应用三个层次的全方位
                            数据安全防护体系。要突破和掌握大数据安全治理的核心关键技术，着力推动在大数据背景下的技术创新。通过加大研发和创新力度，
                            提高数据安全预警、溯源能力，以及应急和处置能力。加强数据防泄露、防窃取、数据加密等技术的研发。数据安全人才短缺的现象
                            也是与会专家关注的焦点，尤其是如何加快培养政企机构急需的安全分析型人才。</p>
                        </div>
                    </div>
                </el-dialog>
                <el-dialog :visible.sync="FZ_Visible" width="50%">
                    <div class="Digital_FZ">
                        <center>
                            <h2>数字经济迎来满园春 展望数字中国发展前景</h2></center><br/>
                        <div class="FZ_bg"></div><br>
                        <div class="FZ_ct">
                            <p>5月6日，《数字中国建设发展报告（2018年）》（以下简称《报告》）在第二届数字中国建设峰会上发布。国家互联网信息办公室副主任杨小伟介绍，数字中国建设取得重要进展，截至2018年年底，中国网民规模达8.29亿，互联网普及率达59.6%，电子信息制造业、软件和信息技术服务业、通信业、大数据产业等保持较快增长。
                            </p><br/>
                            <p><b>数字中国建设取得重要进展:</b>2018年我国新一代信息基础设施加快建设，信息技术创新能力逐步增强。截至2018年年底，全国科技型企业贷款余额为3.53万亿元，各类创新主体创新活力持续释放，我国创新指数在全球排名上升至第17位。
                            </p><br/>
                            <p><b>各地区信息化发展水平整体提升:</b>加快建设数字中国，就是要适应我国发展新的历史方位，全面贯彻新发展理念，以信息化培育新动能，用新动能推动新发展，以新发展创造新辉煌，不断满足人民对美好生活的向往。在区域信息化协调发展方面，更是亮点纷呈。长三角、京津冀、粤港澳等区域信息化协调发展，
                            区域数字经济增长极正在形成，区域网络信息技术创新体系逐步构建，区域信息共享与业务协同水平明显提升。</p><br/>
                            <p><b>缩小数字鸿沟，推动城乡融合发展:</b>今年是全面建成小康社会的关键之年，也是打赢脱贫攻坚战的决战之年。如何通过信息化建设来推动扶贫攻坚和乡村振兴，也成为2019年数字中国建设的着力点之一。“未来，我们将建立城乡信息化融合政策体系和工作机制，统筹推进数字乡村与新型智慧城市建设，
                            促进城乡数据资源等要素合理配置；统筹实施数字乡村发展战略，加快乡村信息基础设施建设，发展农村数字经济，强化农业农村科技创新供给，建设智慧绿色乡村，推进乡村治理能力现代化，深化信息惠民服务，激发乡村振兴内生动力。”杨小伟说，通过巩固提升网络扶贫成效，创新扶贫举措，一定可以打造网络扶贫、数字扶贫升级版
                            </p>
                        </div>
                    </div>
                </el-dialog>
            </div>
        </div>
        <div class="CN_bg1" id="cnbg2">
            <div class="bg1_bt" aos="zoom-in">
                数字经济——推动新发展
            </div>
            <div class="cn_bg1">
                <el-row class="cnjz_bg1">
                    <el-col class="cnjz_bg1_1">
                        <div class="bs-example" style="background-color: transparent;border: 0;" >
                            <div class="cn_row"  style="top: 2vh;" aos="slide-right">
                                <div class="col-sm-6">
                                    <div class="ih-item square colored effect7"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
                                        <a href="/cn_ct1" target="_blank">
                                            <div class="img"><img src="../../assets/images/dchina/szjj1.png" alt="img" style="background-size: 100% 100%;height:30vh"></div>
                                            <div class="info">
                                                <h3>数字经济将重塑中国制造</h3>
                                                <p>查看详情</p>
                                            </div>
                                        </a>
                                    </div>
                                </div>
                            </div> 
                        </div>
                    </el-col>
                    <el-col class="cnjz_bg1_1">
                        <div class="bs-example" style="background-color: transparent;border: 0;" >
                            <div class="cn_row"  style="top: 2vh;" aos="slide-right">
                                <div class="col-sm-6">
                                    <div class="ih-item square colored effect7"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
                                        <a href="/cn_ct2" target="_blank">
                                            <div class="img"><img src="../../assets/images/dchina/szjj2.jpg" alt="img" style="background-size: 100% 100%;height:30vh"></div>
                                            <div class="info">
                                                <h3>25省区市公布上半年成绩单:新兴动能贡献突出</h3>
                                                <p>查看详情</p>
                                            </div>
                                        </a>
                                    </div>
                                </div>
                            </div> 
                        </div>
                    </el-col>
                    <el-col class="cnjz_bg1_1">
                        <div class="bs-example" style="background-color: transparent;border: 0;" >
                            <div class="cn_row"  style="top: 2vh;" aos="slide-left">
                                <div class="col-sm-6">
                                    <div class="ih-item square colored effect7"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
                                        <a href="/cn_ct3" target="_blank">
                                            <div class="img"><img src="../../assets/images/dchina/szjj3.jpg" alt="img" style="background-size: 100% 100%;height:30vh"></div>
                                            <div class="info">
                                                <h3>数字中国建设交出亮眼“成绩单”</h3>
                                                <p>查看详情</p>
                                            </div>
                                        </a>
                                    </div>
                                </div>
                            </div> 
                        </div>
                    </el-col>
                    <el-col class="cnjz_bg1_1">
                        <div class="bs-example" style="background-color: transparent;border: 0;" >
                            <div class="cn_row"  style="top: 2vh;" aos="slide-left">
                                <div class="col-sm-6">
                                    <div class="ih-item square colored effect7"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
                                        <a href="/cn_ct4" target="_blank">
                                            <div class="img"><img src="../../assets/images/dchina/szjj4.jpg" alt="img" style="background-size: 100% 100%;height:30vh"></div>
                                            <div class="info">
                                                <h3>数字经济为中国带来三大红利</h3>
                                                <p>查看详情</p>
                                            </div>
                                        </a>
                                    </div>
                                </div>
                            </div> 
                        </div>
                    </el-col>
                </el-row>
                <el-row class="cnjz_bg1">
                    <el-col class="cnjz_bg1_2">
                        <div class="bs-example" style="background-color: transparent;border: 0;" >
                            <div class="cn_row"  style="top: 2vh;" aos="slide-right">
                                <div class="col-sm-6">
                                    <div class="ih-item square colored effect7"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
                                        <a href="/cn_ct5" target="_blank">
                                            <div class="img"><img src="../../assets/images/dchina/szjj5.jpg" alt="img" style="background-size: 100% 100%;height:30vh"></div>
                                                <div class="info">
                                                    <h3>数字经济是高质量发展的重要推动力</h3>
                                                    <p>查看详情</p>
                                                </div>
                                            </a>
                                    </div>
                                </div>
                            </div> 
                        </div>
                    </el-col>
                    <el-col class="cnjz_bg1_2">
                        <div class="bs-example" style="background-color: transparent;border: 0;" >
                            <div class="cn_row"  style="top: 2vh;" aos="slide-right">
                                <div class="col-sm-6">
                                    <div class="ih-item square colored effect7"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
                                        <a href="/cn_ct6" target="_blank">
                                            <div class="img"><img src="../../assets/images/dchina/szjj6.jpg" alt="img" style="background-size: 100% 100%;height:30vh"></div>
                                            <div class="info">
                                                <h3>5G加速工业互联网释放数字经济增长潜能</h3>
                                                <p>查看详情</p>
                                            </div>
                                        </a>
                                    </div>
                                </div>
                            </div> 
                        </div>
                    </el-col>
                    <el-col class="cnjz_bg1_2">
                        <div class="bs-example" style="background-color: transparent;border: 0;" >
                            <div class="cn_row"  style="top: 2vh;" aos="slide-left">
                                <div class="col-sm-6">
                                    <div class="ih-item square colored effect7"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
                                        <a href="/cn_ct7" target="_blank">
                                            <div class="img"><img src="../../assets/images/dchina/szjj7.jpg" alt="img" style="background-size: 100% 100%;height:30vh"></div>
                                            <div class="info">
                                                <h3>政策红利开启数字经济新空间</h3>
                                                <p>查看详情</p>
                                            </div>
                                        </a>
                                    </div>
                                </div>
                            </div> 
                        </div>
                    </el-col>
                    <el-col class="cnjz_bg1_2">
                        <div class="bs-example" style="background-color: transparent;border: 0;" >
                            <div class="cn_row"  style="top: 2vh;" aos="slide-left">
                                <div class="col-sm-6">
                                    <div class="ih-item square colored effect7"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
                                        <a href="/cn_ct8" target="_blank">
                                            <div class="img"><img src="../../assets/images/dchina/szjj8.jpg" alt="img" style="background-size: 100% 100%;height:30vh"></div>
                                            <div class="info">
                                                <h3>数字经济成发展壮大新动能的重要力量</h3>
                                                <p>查看详情</p>
                                            </div>
                                        </a>
                                    </div>
                                </div>
                            </div> 
                        </div>
                    </el-col>
                </el-row>
            </div>         
        </div>
        <div class="CN_bg2" id="cnbg3">
            <div class="bg2_bt" aos="zoom-in">
                数字经济——推动城市发展
            </div>
            <div class="cn_bg2" aos="flip-up">
                <div class="ct5a">
                    <div class="ct5a1">
                        <br>
                        <h3>深圳</h3>
                        <span>上半年深圳吸收合同外资增幅超40％，跨国巨头相继在深设立创新机构</span>
                        <a></a>
                    </div>
                    <div class="ct5a2">
                        <h4>——深圳是数字经济和未来智慧产业的核心点——</h4>
                    </div>
                    <div class="ct5_ai"></div>
                </div>
                <div class="ct5az">
                    <div class="ct5az_1">
                        <img src="../../assets/images/dchina/szjj9.jpg"  alt="">
                    </div>
                    <div class="ct5az_2">
                        <p>设于深圳的波士顿亚太数字中心是波士顿咨询在亚洲的一个大型综合数字化中心。波士顿咨询强调，这里的数字化专业人才的数量超过传统咨询人员。“深圳的亚太数字中心是BCG的数字转型的技术中心和BCG数字人才的大本营，它将与现有的香港办公室形成合力，服务于粤港澳大湾区企业转型创新。”</p>
                        <p>“深圳是数字经济和未来智慧产业的核心点，有最具吸引力的人力资源和市场信息，这是深圳能够吸引高端服务业外资企业落地的重要原因。”深圳市决策咨询委员会委员、深港科技合作促进会会长张克科认为，高端服务业落地有三大基本要素，即价值链需求、专业人才需求和市场需求。“从上述三要素来看，此轮跨国企业进入深圳，应该是面向未来，认为深圳在整个中国经济发展体系中是最具有开放性、最具改革机会的城市之一，同时深圳也是‘一带一路’和粤港澳大湾区建设中一个最具先行先试机会的城市。你要了解中国，那么你必须到深圳来。”</p>
                    </div>
                </div>

                <div class="ct5b">
                <div class="ct5b1">
                    <br>
                    <h3>浙江</h3>
                    <span>数字经济引领浙江高质量发展</span>
                    <a></a>
                </div>
                <div class="ct5b2">
                    <h4>——产业互联，数造未来——</h4>
                </div>
                <div class="ct5_bi"></div>
                </div>
                <div class="ct5bz">
                    <div class="ct5bz_1">
                        <img src="../../assets/images/dchina/szjj10.jpg" alt="">
                    </div>
                    <div class="ct5bz_2">
                        <p><b>数字经济改变生活生产。</b>据统计，2018年，浙江网络零售额16719亿元，增长25.4%；省内居民网络消费8470.5亿元，增长25.0%。与线上消费相关的快递业务量达101.1亿件，比上年增长27.5%，业务收入779.3亿元，增长16.6%。
                        而在工业生产领域，近年来，浙江推进工业互联网与智能制造融合，着力开展“工业互联网+智能制造”融合示范试点，推进大数据、人工智能与实体企业智能制造深度融合，通过系统构建网络、平台、安全三大功能体系，形成产业数字化的新兴业态和应用模式。
                        </p>
                        <p><b>技术创新推动供给侧结构性改革。</b>数据显示，浙江省数字经济核心产业增加值2015、2016、2017、2018年分别比上年增长15.1%、15.9%、16.7%、13.1%，2018年已占全省GDP的9.9%。</p>
                        <p><b>创新创业精神与互联网基因叠加产生倍增效应。</b>
                        数字经济是创新创业经济，浙江人‘敢为人先，特别能创业’的草根创业精神，一旦植入了‘互联网基因’，将叠加产生倍增效应。”陈畴镛说。
                        眼下，创新创业人才正加速向浙江集聚，浙大系、阿里系、海归系和浙商系等创业创新“新四军”异军突起，活跃在数字经济新空间。</p>
                    </div>
                </div>

                <div class="ct5c">
                <div class="ct5c1">
                    <br>
                    <h3>贵阳</h3>
                    <span>贵阳高新区：以大数据引领高质量发展</span>
                    <a></a>
                </div>
                <div class="ct5c2">
                    <h4>——贵阳高新区——</h4>
                </div>
                <div class="ct5_ci"></div>
                </div>
                <div class="ct5cz">
                    <div class="ct5cz_1">
                        <img src="../../assets/images/dchina/szjj11.jpg"  alt="">
                    </div>
                    <div class="ct5cz_2">
                        <p>作为全省、全市大数据发展的主战场、核心区之一，近年来，贵阳国家高新区以大数据引领高质量发展，形成较为完整的产业发展生态,呈现出产业加快聚集、行业深度融合、创新能力显著增强、信息基础设施不断改善的良好态势。大数据成为引领数字经济,促进社会经济高质量发展的强大引擎，为发展不断催生新动能。</p>
                        <p>在精准施政方面。高新区建立了辖区数据共享工作及大数据政用系统建设开发的 “1+12N+1”体系架构。构建了数聚高新一体化平台，完成了共性设施层的25个组件，搭建了共享交换平台、大数据分析平台和快速开发平台三个平台应用。</p>
                        <p>今后，高新区将持续推进大数据聚通用，加快建设政府数据共享平台，加强政府部门数据资源横向整合和管理，加强与国家有关机构的数据互换、信息互通，实施政务数据资源整合计划，打造大数据实现高水平治理示范区。</p>
                    </div>
                </div>

                <div class="ct5d">
                <div class="ct5d1">
                    <br>
                    <h3>南京</h3>
                    <span>“数字经济”点亮南京未来</span>
                    <a></a>
                </div>
                <div class="ct5d2">
                    <h4>——打造数字经济名城——</h4>
                </div>
                <div class="ct5_di"></div>
                </div>
                <div class="ct5dz">
                    <div class="ct5dz_1">
                        <img src="../../assets/images/dchina/szjj13.jpg" alt="">
                    </div>
                    <div class="ct5dz_2">
                        <p>在数字基础设施方面，南京是全国五个通信枢纽、十个国家级互联网骨干直联点和全国互联网八大节点之一，也是“宽带中国”首批示范城市，数字基础设施相对完善，数字经济发展基础支撑条件良好。</p>
                        <p>在“数字产业化”方面，南京是全国首个“中国软件名城”，软件与信息服务业、电子信息制造业等数字经济核心产业是南京重点发展的主导产业，在全国具有较强的竞争力。软件与信息服务业优势尤其明显，软件业务收入规模继续保持全省第一、全国第四，电力系统软件、通信软件、智能交通软件分别占据国内50%、30%、20%以上的市场份额，江苏省的8家软件业务收入百强企业全部在南京，国家规划布局内重点软件企业，南京有16家，占全省70%。</p>
                        <p>在电子信息制造业领域，南京拥有三个“千亿级产业”，分别是新型显示产业、信息通讯设备产业、物联网产业，近年引进落户了台积电、紫光展锐、中兴通讯南京滨江智能制造基地、格力空调智能制造基地等一大批龙头企业、龙头项目，产业支撑力量强大。</p>
                    </div>
                </div>
                
                
                <div class="ct5e">
                <div class="ct5e1">
                    <br>
                    <h3>福州</h3>
                    <span>多措并举推进"数字福州"建设 今年力争实现数字经济占GDP比重超37.5%</span>
                    <a></a>
                </div>
                <div class="ct5e2">
                    <h4>——"数字福州"建设——</h4>
                </div>
                <div class="ct5_ei"></div>
                </div>
                <div class="ct5ez">
                    <div class="ct5ez_1">
                        <img src="../../assets/images/dchina/szjj14.jpg" alt="">
                    </div>
                    <div class="ct5ez_2">
                        <p>在推进数字经济产业集群发展方面，福州将重点发展福州软件园、海西高新区、马尾物联网产业园、融侨经济技术开发区、东南大数据产业园等特色数字经济园区，壮大显示、光电芯片、物联网、大数据、软件信息等五大产业基地，支持各产业基地重点培育"独角兽""单项冠军""专精特新"企业。</p>
                        <p>在大数据发展方面，福州将加快培育大数据产业基地，依托东南大数据产业园，充分发挥行业龙头企业引领示范作用，带动大数据产业整体能级提升，持续优化大数据企业发展环境，主动兑现企业优惠政策，加快聚集各类创新要素。</p>
                        <p>打造区块链经济综合试验区，筹建比特大陆区块链研究中心，争取开展3至5项区块链技术重点行业应用示范。同时，打造一批人工智能创新示范平台和人工智能领军企业，加快推动永泰人工智能小镇等建设，建成福建省人工智能超算平台二期。</p>
                    </div>
                </div>
            <script src="js/cn_bg2.js"></script>
            </div>
        </div>
        <div class="CN_bg4" id="cnbg5">
            <div class="bg4_header">
                <div class="bg4_bk1">
                    <div class="video_bt" aos="zoom-in">
                        看“数字经济”
                    </div>
                    <div class="CN_video">
                            <span>
                                <div class="cn_v01 cn_v wow bounceInRight" @click="VideoVisible1=true"></div>
                                <el-dialog :visible.sync="VideoVisible1">
                                    <video controls="controls" width="100%" autoplay="autoplay">
                                        <source src="../..//assets/video/china_video1.mp4" type="video/mp4">
                                    </video>
                                    <h3>贵阳高新区：补短板强实体 上半年经济发展稳中有进</h3>
                                </el-dialog>
                            </span>
                            <span>
                                <div class="cn_v06 cn_v wow bounceInRight" @click="VideoVisible2=true"></div>
                                <el-dialog :visible.sync="VideoVisible2">
                                    <video controls="controls" width="100%" autoplay="autoplay">
                                        <source src="../..//assets/video/china_video2.mp4" type="video/mp4">
                                    </video>
                                    <h3>[中国新闻]聚焦中国两会贵州：发展大数据让经济高质量发展</h3>
                                </el-dialog>
                            </span>
                            <span>
                                <div class="cn_v02 cn_v wow bounceInRight" @click="VideoVisible3=true"></div>
                                <el-dialog :visible.sync="VideoVisible3">
                                    <video controls="controls" width="100%" autoplay="autoplay">
                                        <source src="../..//assets/video/china_video3.mp4" type="video/mp4">
                                    </video>
                                    <h3>[第一时间]聚焦2019贵阳数博会数博会首设扶贫展大数据牵手“农产品”</h3>
                                </el-dialog>
                            </span>
                            <span>
                                <div class="cn_v03 cn_v wow bounceInLeft" @click="VideoVisible4=true"></div>
                                <el-dialog :visible.sync="VideoVisible4">
                                    <video controls="controls" width="100%" autoplay="autoplay">
                                        <source src="../..//assets/video/china_video4.mp4" type="video/mp4">
                                    </video>
                                    <h3>[贵州新闻联播]大数据与实体经济深度融合全国行首站在贵阳启动</h3>
                                </el-dialog>
                            </span>
                            <span>
                                <div class="cn_v04 cn_v wow bounceInLeft" @click="VideoVisible5=true"></div>
                                <el-dialog :visible.sync="VideoVisible5">
                                    <video controls="controls" width="100%" autoplay="autoplay">
                                        <source src="../..//assets/video/china_video5.mp4" type="video/mp4">
                                    </video>
                                    <h3>[经济信息联播]聚焦2019贵阳数博会贵州：大数据助力乡村经济发展</h3>
                                </el-dialog>
                            </span>
                            <span>
                                <div class="cn_v05 cn_v wow bounceInLeft" @click="VideoVisible6=true"></div>
                                <el-dialog :visible.sync="VideoVisible6">
                                    <video controls="controls" width="100%" autoplay="autoplay">
                                        <source src="../..//assets/video/china_video6.mp4" type="video/mp4">
                                    </video>
                                    <h3>[视频]贵州：大数据产业推动社会经济发展</h3>
                                </el-dialog>
                            </span>
                    </div>
                </div>
            </div>
        </div>
        <div class="CN_bg6"  id="cnbg6">
            <div class="bg4_footer">
                <div class="CN_yuan">
                    <div class="CN_yuan1"></div>
                    <div class="bg4_bt" aos="zoom-in">县域经济发展</div>
                    <div class="CN_yuan2"></div>
                </div>
                <div class="bg4_bk2">
                    <div class="footer_left">
                        <a href="/cn_ct9" style="color:white" target="_blank">
                            <div class="left_ct" aos="fade-up">
                            <h3>远程医疗</h3>
                                <p>
                                    足不出村，通过远程连线，山东高青常家镇蓑衣樊村村医坐在卫生室里，就可以与400公里外的北京301医院的专家一同给村民会诊。
                                    远程医疗是高青县智慧城市建设的重要一环。这个不足40万人口的鲁中小城，利用物联网、大数据、云计算等先进技术手段赋能城市管理，力图实现善政、惠民、兴业。
                                </p>
                            </div>
                            <div class="left_img" aos="fade-up">
                                <div class="img_ct">
                                <p>
                                    智慧城市，以往集中于中国的一二线城市，以及部分较发达的三线城市。如今越来越多像高青这样的县级城市，投身到智慧城市建设的热潮中。智慧城市在解决“大城市病”的同时，往县域延伸助力基层破解发展难题。
                                </p>
                                <p>
                                    近几年，中国智慧城市建设方兴未艾。人民网研究院副院长唐胜宏介绍，据不完全统计，目前中国100%的副省级以上城市、93%的地级以上城市、部分县级市，总共约有700个城市已经提出或正在建设智慧城市，占到同期全球提出创建智慧城市总量的70%。
                                </p>
                                </div>
                            <div class="cn1_img"></div>
                            </div>
                        </a>
                    </div>
                </div>
                <div class="bg4_bk3">
                    <div class="footer_right">
                        <a href="/cn_ct10" style="color:white" target="_blank">
                            <div class="right_ct" aos="fade-up">
                                <h3>县域智慧城市建设</h3>
                                <p>
                                    互联网、云计算、大数据、物联网等飞速更新的信息通讯技术正深刻重塑着交通、医疗、农业、金融、通信、社会治理等应用场景。
                                    与此同时，随着智慧城市建设不断引向深入，智慧城市发展明显呈现出从大中城市向中小城市，尤其是向县域地区普及的发展态势。
                                </p>
                            </div>
                            <div class="right_img" aos="fade-up">
                                <p>
                                   县域政府连接城镇与广大的乡村，智慧县城建设是实现数字中国不可缺少的节点，在促进县域经济转型升级方面的作用愈发凸显。
                                   与会嘉宾表示，未来我国智慧城市建设的深度重点，体现在县域地区如何利用创新要素完成县域智慧城市的普及和实践，县域地区开展智慧城市建设是我国未来智慧城市建设的重要工作。 
                                </p>
                                <div class="cn2_img"></div>
                            </div>
                            </a>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>

// if (process.browser) { // 在这里根据环境引入wow.js
//     var {WOW} = require('wowjs')
//     }

export default {
    head:{
        script:[
            {src:'js/jquery.1.7.1.min.js'},
            {src:'js/jquery.min.js'},
            {src:'js/aos.js'},
            {src:'js/cn_app.js'},
        ],
        link: [
            { rel: 'stylesheet', href: 'css/normalize.css' },
            { rel: 'stylesheet', href: 'css/demo.css' },
            { rel: 'stylesheet', href: 'js/aos.css' },
            { rel: 'stylesheet', href: 'css/styles.css' },
            { rel: 'stylesheet', href:'css/cn_main.css'},
        ]
    },
    data(){
        return{
            VideoVisible1: false,VideoVisible2: false,
            VideoVisible3: false,VideoVisible4: false,
            VideoVisible5: false,VideoVisible6: false,
            TZ_Visible: false,JZ_Visible: false,
            JY_Visible: false,RH_Visible: false,
            YY_Visible: false,FZ_Visible: false
        }
    },
    mounted() {
        AOS.init({
            easing: 'ease-out-back',
            duration: 1000
        });
        // if (process.browser) {  // 在页面mounted生命周期里面 根据环境实例化WOW
        //     new WOW({
        //         live: true, 
        //         offset: 0
        //     }).init()
        // };
    }
}
</script>

<style>
    @import "@/assets/css/digital_china.css";
</style>