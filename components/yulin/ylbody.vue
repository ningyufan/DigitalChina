<template>
    <div>	
		<!-- 数字玉林·智慧城市建设板块内容 -->
        <div id="box_cs" class="bk_cs">
            <el-row class="title_text" aos="zoom-in" >
                数字玉林·智慧城市建设
			</el-row>
			<el-row style="width: 100vw;height: 80vh;top: 7vh;">
				<div id="content" aos="flip-up">
					<!--特效部分-->
					<ul class="accordion" id="accordion">
						<li class="bg1" >
							<div class="heading">玉林"智慧人大"平台</div>
							<div class="bgDescription"></div>
							<div class="description" >
								<h2>玉林"智慧人大"平台</h2>
								<p>玉林“智慧人大”管理平台包括电脑端（PC）和手机客户端（APP端），主要有“立法系统”、“监督系统”、“代表履职系统”、“办公系统”...</p>
								<a @click="cs_dialog1 = true">更多 &rarr;</a>
							</div>
						</li> 
						<li class="bg2">
							<div class="heading">玉林城市普惠平台</div>
							<div class="bgDescription"></div>
							<div class="description">
								<h2>玉林城市普惠平台</h2>
								<p>玉林市总工会、玉林市区农村信用合作联社以及广西金拇指网络科技信息有限公司联合创新打造了一个“银行+智慧城市商家联盟+工会会员”...</p>
								<a @click="cs_dialog2 = true">更多 &rarr;</a>
							</div>
						</li> 
						<li class="bg3">
							<div class="heading">发力数字玉林建设</div>
							<div class="bgDescription"></div>
							<div class="description">
								<h2>发力数字玉林建设</h2>
								<p>在当前“深入实施大数据战略加快数字广西建设”的大潮中，中国电信玉林分公司在现有全光网络的基础上，进一步加大投入、升级网络能力...</p>
								<a @click="cs_dialog3 = true">更多 &rarr;</a>
							</div>
						</li>
						<li class="bg4">
							<div class="heading">玉林市大数据研究院</div>
							<div class="bgDescription"></div>
							<div class="description">
								<h2>玉林市大数据研究院</h2>
								<p>以玉林市大数据中心、玉林师范学院大数据应用创新中心、广西高校复杂系统优化与大数据处理重点实验室为依托...</p>
								<a @click="cs_dialog4 = true">更多 &rarr;</a>
							</div>
						</li>
						<li class="bg5">
							<div class="heading">“智慧玉林”签约启动</div>
							<div class="bgDescription"></div>
							<div class="description">
								<h2>“智慧玉林”签约启动</h2>
								<p>2016年11月7日，玉林市智慧城市建设座谈会暨签约仪式在南宁举行，玉林市政府与曙光云计算有限公司就玉林市智慧城市建设项目进行签约...</p>
								<a @click="cs_dialog5 = true">更多 &rarr;</a>
							</div>
						</li>
						<li class="bg6 bleft">
							<div class="heading">入选“国家智慧城市”</div>
							<div class="bgDescription"></div>
							<div class="description">
								<h2>入选“国家智慧城市”</h2>
								<p>2015年4月，玉林市入选国家智慧城市试点。创建智慧城市活动，是玉林市“三个年一活动”的重要内容和有力载体...</p>
								<a @click="cs_dialog6 = true">更多 &rarr;</a>
							</div>
						</li>
					</ul>
					<!--特效结束-->
				</div>
				<!-- 智慧城市建设弹出框内容 -->
				<el-dialog
					title="玉林“智慧人大”管理平台正式启用"
					:visible.sync="cs_dialog1"
					width="60%"
					center
					@close="close_video">
					<span>
						<div class="dialog-video1">
							<video src="@/assets/video/yl_video1.mp4" controls="controls" autoplay="autoplay" width="74%" height="25%" id="video1"></video>
						</div>
						<br>
						<div class="font-content">
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;近年来，玉林市人大常委会立足新时代的新形势新要求，高度重视人大机关信息化建设，以玉林“智慧人大”管理平台为切入口，不断提升人大履职水平，逐步实现玉林人大的办公高效化、监督智能化、服务便捷化。</p>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;据悉，玉林“智慧人大”管理平台包括电脑端（PC）和手机客户端（APP端），主要有“立法系统”、“监督系统”、“代表履职系统”、“办公系统”、“信息系统”等5大功能系统、30多个子系统。通过该系统，将使人大机关办公更加便捷、高效，立法、监督等各项职能实现“互联网+”，代表履职管理和议案、建议办理“一键通”。</p>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;玉林“智慧人大”管理平台的开通使用，标志着玉林人大正式迈进智能时代。下一步，玉林人大将着重在完善应用、功能优化、互联共享上下功夫，努力将平台打造成玉林人大建设的新品牌、新名片。</p>
						</div>
					</span>
				</el-dialog>
				<el-dialog
					title="玉林智慧城市工会会员普惠平台亮相玉博会"
					:visible.sync="cs_dialog2"
					width="60%"
					center>
					<span>
						<div class="dialog-img">
							<img src="@/static/images/city_p2.jpg" alt="" width="70%" height="30%">
						</div>
						<br>
						<div class="font-content">
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;9月15日，记者在第十二届玉博会展馆看到，中国—东盟小商品交易中心三楼的玉林智慧城市工会会员普惠平台馆门庭若市，门口小机器人逗乐往来行人，记者了解到，玉林市总工会、玉林市区农村信用合作联社以及广西金拇指网络科技信息有限公司联合创新打造了一个“银行+智慧城市商家联盟+工会会员”普惠化服务平台，平台通过建成一张融合工会服务、商业服务、金融服务、互联网服务等主要功能的“广西（玉林）工会会员服务卡”，扩大工会会员的享受服务范围，实现全市惠工行动“服务主体更广泛、服务内容更丰富、服务质量更保证、服务方式更便捷、服务对象全覆盖，多方共赢”的总体目标。</p>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;据现场工作人员介绍，“广西（玉林）工会会员服务卡”不同于普通的银行卡，既有金融IC卡功能和签约商家特惠服务功能，又有会员管理和相关服务功能，实现一卡多用及多行业应用的效果。目前，持卡会员可享受工会组织所属服务机构提供的免费或普惠服务，生活救助、医疗救助、金秋助学等工会帮扶资金均可通过“广西（玉林）工会会员服务卡”发放；能享受区内相应公共服务“一卡通”的各种便利和实惠服务；还享有银行会员的各项实惠服务。另外，持卡会员能便捷地获取本地签约商家的优惠、福利信息，在商家消费指定商品及服务，将获得相应的让利折扣。</p>
						</div>
					</span>
				</el-dialog>
				<el-dialog
					title="玉林电信：发力智慧城市建设 助力数字广西发展"
					:visible.sync="cs_dialog3"
					width="60%"
					center>
					<span>
						<div class="dialog-img">
							<img src="@/static/images/city_p3.png" alt="" width="70%" height="30%" >
						</div>
						<br>
						<div class="font-content">
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;中国电信积极推进智慧城市建设，在智慧政务、智慧产业和智慧民生三个领域为广大用户提供综合、便捷、个性化的服务，进一步推动城镇化、信息化和工业化发展。</p>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;中国电信作为信息化建设的“国家队”“主力军”，中国电信玉林分公司于2015年9月，在玉林市通信业界率先建成智慧城市体验厅，成为全玉林首家以智慧城市命名、展现智慧城市建设主题内容的综合性互动式体验科普厅店。设置了智慧城市形象展示区和智慧政务、智慧产业、智慧民生三个版块体验区，通过多媒体、展板、实物展示、人工讲解等方式，结合各行业、各类群体工作、生活中实际应用场景，搭建智慧应用的体验环境，让前来体验的人们亲身感受到云计算、物联网、大数据、互联网+、人工智能等新一代信息技术给我们带来的高效及便捷，让“智慧城市”看得见、摸得着，进而促进玉林市的信息化应用水平的提升。</p>
						</div>
					</span>
				</el-dialog>
				<el-dialog
					title="玉林市大数据研究院"
					:visible.sync="cs_dialog4"
					width="60%"
					center>
					<span>
						<div class="dialog-img">
							<img src="@/static/images/city_p4.png" alt="" width="38%" height="30%" >
							<img src="@/static/images/city_p4_1.png" alt="" width="38%" height="30%" >
						</div>
						<br>
						<div class="font-content">
							<span style="font-size: 2vh;font-weight:550;">四个研究领域:</span><br>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 围绕广西壮族自治区人民政府印发《促进大数据发展的行动方案》（桂政发【2016】59号），结合地方政府和产业发展需要凝炼科研方向，主要关注教育大数据、农业大数据、旅游侨务大数据、健康医疗大数据等研究领域。</p>
							<span style="font-size: 2vh;font-weight:550;">建设目标:</span><br>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;以玉林市大数据中心、玉林师范学院大数据应用创新中心、广西高校复杂系统优化与大数据处理重点实验室为依托，把玉林市大数据研究院建成一个面向全市乃至全区的行业大数据研究机构，为全市及全区的大数据产业发展提供技术支撑和服务，形成利用科研能力提供行业服务，利用行业服务实现人才培养，利用人才培养支撑科研能力建设的良性循环。</p>
						</div>
					</span>
				</el-dialog>
				<el-dialog
					title="玉林市智慧城市建设签约仪式在南宁举行"
					:visible.sync="cs_dialog5"
					width="60%"
					center>
					<span>
						<div class="dialog-img">
							<img src="@/static/images/city_p5.png"  width="70%" height="30%" >
						</div>
						<br>
						<div class="font-content">
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;11月7日，玉林智慧城市建设座谈会暨签约仪式在南宁举行。玉林市政府与曙光云计算有限公司签订了榆林智慧城市建设项目合同，标志着“智慧玉林”项目正式启动实施。市长苏海棠、副市长李振平，曙光信息产业有限公司董事、高级副总裁，曙光云计算有限公司总裁聂华出席签约仪式。</p>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;苏海棠感谢聂华一行的到来，向他们汇报了榆林市经济社会发展，特别是城市信息化建设情况。他说，“智慧城市”是城市信息化发展的高级阶段，是对城市管理、公共服务、民生保障、商业活动等城市需求的智能回应。这对完善政府管理，提高居民生活质量具有重要意义。近年来，我市高度重视城市信息化建设，在电子政务和信息网络建设方面取得了显著成就，为榆林市“智慧城市”建设打下了良好的基础。榆林市签约的“智慧城市”建设项目包括智能政务平台、智能社区、智能园区、智能药都等19个项目。按照“统筹规划、分步实施”的原则推进。项目建成后，将实现城市智能化管理、政府科学决策、特色化生产。工业的发展对经济的发展有很大的促进作用。在未来的建设中，我们衷心希望广西中科曙光云计算有限公司（以下简称中科曙光）发挥技术和资源优势，全力推进项目建设，确保玉林“智慧城市”建设项目城市将成为“智慧城市”建设的示范工程。</p>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;聂华在听取汇报后，对玉林经济社会发展取得的成绩表示高兴，并对能够参与玉林“智慧城市”建设感到荣幸。未来，中科曙光将以最优秀的技术和最大的力量投入到项目建设中，与玉林市政府共同谱写“让玉林更智慧，让生活更幸福”的“智慧玉林”新篇章。</p>
						</div>
					</span>
				</el-dialog>
				<el-dialog
					title="Yulin City Selected as National Smart City "
					:visible.sync="cs_dialog6"
					width="60%"
					center>
					<span>
						<div class="dialog-img">
							<img src="@/static/images/city_p6.png"  width="50%" height="30%">
						</div>
						<br>
						<div class="font-content">
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2015年4月，我市入选国家智慧城市试点。创建智慧城市是与玉林市“三年一活动”的重要内容和有力载体。在前期工作的基础上，创作工作进入了顶层设计阶段。稳步实施16个项目，建设国家级智慧城市需要3-5年时间。</p>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;我市创建国家智慧城市的目标，主要是通过创建智慧城市，提高城市规划建设的科学性，提高城市管理的效率和精细化，改善公共服务，明智地推进玉林新型城镇化建设。改善民生，促进产业转型升级，全面促进经济社会发展。城市管理智能化、民生幸福化、产业转型升级框架；信息技术全面支撑榆林经济社会快速可持续发展，城市运行状况全面可视化，综合防范和控制城市安全，有效支持城市经营管理决策；进一步改善民生，提供社会公共服务。实现公平便捷发展，人民幸福感倍增，建设服务型政府；实现经济良性转型升级，基本建成智慧型北部湾中心城市。</p>
						</div>
					</span>
				</el-dialog>
            </el-row> 
		</div>
		<!-- <canvas id="canvas" width="100%"  height="auto" style="position: absolute;width:auto">
		</canvas>
		<script src='js/yl_b.js'></script> -->
		<!-- 数字玉林·“互联网+”政务服务板块 -->
		<div style="position: relative;z-index:1">
        <div id="box_zw" class="bk_zw">
            <el-row class="title_text" aos="zoom-in" style="position: relative;z-index:2">数字玉林·“互联网+”政务服务</el-row>
			<el-row class="zhengwu_module1" aos="fade-up" style="position: relative;z-index:2">
				<template v-if="zw_click == 0">
					<div class="zw_content">
						<p class="zw_ctTitle">插上“科技”翅膀 点亮玉林智慧法院新名片</p>
						<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;今年以来，玉林市中级人民法院以问题为导向，以应用为目标，以创新为手段，准确把握云计算、大数据等信息技术的新进展新应用，大力推进“智慧法院”建设，推出多项玉林模式的新举措，打造智慧法院玉林模式。</p>
						<p style="font-weight:550;">全业务网上办理——打造新型网络法院</p>
						<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2018年1- 11月，全市法院共受理各类案件37522件，同比上升6.56%，其中受理诉讼案件28111件，同比上升4.02%，受理执行案件9411件，同比上升14.94%，受理刑事案件3583件，同比上升0.14%，民商事案件23338件，同比上升2.23%，法定审限内审结率100%。以上数据均来自于玉林市中级人民法院“智慧法院”系统的线上实时统计。</p>
						<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在玉林市两级法院，所有案件从立案到归档，二维码立案、随机分案、文书智能编写、一键归档、案件流程公开等系统全面应用，融合案件审理各个阶段的科技法庭、远程接访、指挥中心、远程提讯等信息化场所的运用，案件进展看得见，实现对审判执行活动的动态监控，加强对审判权、执行权运行中每个环节的监督制约，规范司法行为。</p>
						<p style="font-weight:550;">全流程依法公开——打造阳光法院</p>
						<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“案件流程公开”“庭审直播”“裁判文书上网”“执行信息公开”……这些信息系统，打开了法院案件信息公开的通道，让司法在阳光下运行，接受群众及媒体监督，进一步提升司法公信力。全市法院力推上网公开裁判文书及庭审直播，不断扩大裁判文书公开范围及直播案件的数量。截止今年11月29日，全市已建科技法庭64个，记录庭审活动65000多件/次，裁判文书上网66723份，上网率100%，庭审直播7132件。</p>
						<p style="font-weight:550;">全方位智能服务——打造智能法院</p>
						<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;让数据多跑路，让群众少跑腿”——这是全市法院建设智能型法院的重要目标。自从2015年全国法院落实立案登记制度以来，诉讼案件大幅增加，全市法院积极作为，主动引入科技手段，致力于提高服务群众诉讼的能力，让当事人方便快捷参与诉讼。</p>
					</div>
				</template>
				<template v-if="zw_click == 1">
					<div class="zw_content">
						<p  class="zw_ctTitle">玉林市部署大数据发展和政务服务工作 建设数字玉林 服务“东融”战略</p>
						<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;近日，我市（玉林市）召开2019年全市大数据发展和政务服务工作会议，本次会议是机构改革全市大数据发展和政务服务工作整合后的第一次会议，对加快我市大数据发展、深化“放管服”改革、全面提升政务服务工作质量具有重要意义。市委常委、常务副市长丘德奎出席会议。</p>
						<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;丘德奎强调，大数据发展已经上升到国家战略，我们要全面贯彻落实国家大数据发展战略，高起点谋划，高质量推进，大力建设数字玉林，坚持“六个强化”：强化责任担当，开创大数据发展和政务服务新局面；强化设施建设，夯实数字发展基础；强化产业融合，促进数字经济蓬勃发展；强化“百日攻坚”活动，服务“东融”战略实施；强化政务服务“简易办”，不断提升为民服务能力；强化电子政务，促进政府公信力提升，奋力开创新时代全市大数据发展和政务服务事业新局面。</p>
						<br>
						<br>
					</div>
				</template>
				<template v-if="zw_click == 2">
					<div class="zw_content">
						<p class="zw_ctTitle">玉林市召开全市大数据发展和政务服务工作会议吹响大数据发展号角</p>
						<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4月26日，2019年全市大数据发展和政务服务工作会议在市文化艺术中心召开，正式吹响大数据发展号角。这是机构改革全市大数据发展和政务服务工作整合后的第一次会议，对加快我市大数据发展，深化“放管服”改革，全面提升政务服务工作质量，具有里程碑意义。</p>
						<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;会上，市大数据发展和政务服务局局长蒋祥宋就推进大数据发展和政务服务工作作报告。市委常委、常务副市长丘德奎对我市上一年度政务服务工作和坚持数字战略驱动策略，研产结合，全力推进前沿信息、电子商务等产业发展所取得的成果表示肯定。丘德奎强调，大数据发展已经上升到国家战略，我们要全面贯彻落实国家大数据发展战略，高起点谋划，高质量推进，大力建设数字玉林，坚持“六个强化”：强化责任担当，开创大数据发展和政务服务新局面；强化设施建设，夯实数字发展基础；强化产业融合，促进数字经济蓬勃发展；强化“百日攻坚”活动，服务“东融”战略实施；强化政务服务“简易办”，不断提升为民服务能力；强化电子政务，促进政府公信力提升，奋力开创新时代全市大数据发展和政务服务事业新局面，为我市打好“三大会战”，实现“六大突破”，提供坚实的保障。</p>
					</div>
				</template>
				<template v-if="zw_click == 3">
					<div class="zw_content">
						<p class="zw_ctTitle">玉林市大数据发展和政务服务局：从“能够办”向“简易办”转变</p>
						<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;玉林新闻网-玉林日报讯（记者 张冠中）记者日前从玉林市大数据发展和政务服务局了解到，今年以来，玉林市加快数字政务建设，政务服务从实体大厅到线上线下融合，从“能够办”向“简易办”转变，以减环节、减时限、减材料、减成本、减跑腿的“五个减少”进一步提升政府服务企业、群众的能力和水平。</p>
						<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;其中，在减时限方面，从串联审批到并联审批。玉林市主动改革审批方式，从环节先后衔接的串联审批向同步推进的并联审批转变。再造并梳理投资项目审批服务全流程，项目审批总的办理时限最大减少82%；再造不动产登记全流程，办结时限比原来缩短时间约60%；再造企业开办流程，企业信息同步推送，企业开办时间从15天压缩到1天办结。</p>
						<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在减材料方面，从“多次跑”到“跑一次”。从申报材料入手，加强数据共享，取消重复递交的材料，简化材料为表格，编制材料清单，促进“最多跑一次”。市本级在全区率先公布各个部门“三张清单”，“最多跑一次”事项1191项，比例达99.34%，县（市、区）级“最多跑一次”达到91.93%，乡镇为98.97%。</p>
						<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在减跑腿方面，从线下办事到数字政务。实施大数据发展战略推进网上办事，目前市本级网上咨询申请办事事项达1074项，占总办理事项的92.11%，居全区前列。比如，我市目前已经搭建新一代智慧公积金信息平台，刷脸开户、网上缴存、退休提取、离职提取等业务实行“不见面审批”服务新模式，在全区首次实现住房公积金贷款自主核算、征信自主报送同步切换、无缝衔接。全面推进企业名称自主申报改革试点，实行电子营业执照和全程电子化登记管理，实现各类企业、个体工商户、农民专业合作社在线直接领取电子营业执照，足不出户“网上办照”。 </p>
					</div>
				</template>
			</el-row>
			<el-row class="zhengwu_module2" aos="flip-right" style="position: relative;z-index:2">
				<el-col class="zhengwu_module2_1">
					<div class="bs-example" style="background-color: transparent;border: 0;" >
						<div class="yl_row"  style="top: 2vh;">
							<div class="col-sm-6">
								<div class="ih-item square effect3 bottom_to_top"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
									<div @click="zw_click = 0">
									<a>
										<div class="img">
											<img src="@/assets/images/yulin/zw_p2.jpg" alt="img" style="background-size: 100% 100%;">
										</div>
										<div class="info">
											<p style="font-size: 1.5vh;color:cyan;border-bottom:1px solid rgb(255, 255, 255);">玉林市大数据发展和政务服务局：插上“科技”翅膀 点亮玉林智慧法院新名片</p>
										</div>
									</a>
								</div>
								</div>
							</div>
						</div> 
					</div>
				</el-col>
				
				<el-col class="zhengwu_module2_1">
					<div class="bs-example" style="background-color: transparent;border: 0;" >
						<div class="yl_row"  style="top: 2vh;">
							<div class="col-sm-6">
								<div class="ih-item square effect3 bottom_to_top"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
									<div @click="zw_click = 1">
									<a >
										<div class="img">
											<img src="@/assets/images/yulin/zw_p3.jpg" alt="img" style="background-size: 100% 100%;">
										</div>
										<div class="info">
											<p style="font-size: 1.5vh;color:cyan;border-bottom:1px solid rgb(255, 255, 255);">玉林市部署大数据发展和政务服务工作 建设数字玉林 服务“东融”战略</p>
										</div>
									</a>
								</div>
								</div>
							</div>
						</div> 
					</div>
				</el-col>
				<el-col class="zhengwu_module2_1" >
						<div class="bs-example" style="background-color: transparent;border: 0;" >
							<div class="yl_row"  style="top: 2vh;">
								<div class="col-sm-6">
									<div class="ih-item square effect3 bottom_to_top"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
										<div @click="zw_click = 2">
										<a >
											<div class="img">
												<img src="@/assets/images/yulin/zw_p1.jpg" alt="img" style="background-size: 100% 100%;">
											</div>
											<div class="info">
												<p style="font-size: 1.5vh;color:cyan;border-bottom:1px solid rgb(255, 255, 255);">玉林市召开2019年全市大数据发展和政务服务工作会议 吹响大数据发展号角</p>
											</div> 
										</a>
									</div>
									</div>
								</div>
							</div> 
						</div>
					</el-col>
				<el-col class="zhengwu_module2_1">
					<div class="bs-example" style="background-color: transparent;border: 0;" >
						<div class="yl_row">
							<div class="col-sm-6">
								<div class="ih-item square effect3 bottom_to_top"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
									<div @click="zw_click = 3">
										<a >
											<div class="img">
												<img src="@/assets/images/yulin/zw_p4.jpg" alt="img" style="background-size: 100% 100%;">
											</div>
											<div class="info">
												<p style="font-size: 1.5vh;color:cyan;border-bottom:1px solid rgb(255, 255, 255);">玉林市大数据发展和政务服务局：从“能够办”向“简易办”转变</p>
											</div>
										</a>
									</div>
								</div>
							</div>
						</div> 
					</div>
				</el-col> 
			</el-row>
		
		</div>
		<!-- <div id="background" class="wall"></div> -->
		<div id="midground" class="wall"></div>
		<div id="foreground" class="wall"></div>
		<div id="top" class="wall"></div>

		<!-- 数字玉林·智慧旅游建设板块内容 -->
			<div id="box_ly" class="bk_ly">
                    <el-row class="title_text" aos="zoom-in">
                        数字玉林·智慧旅游建设
					</el-row>
					<el-row class="travel_module1">
						<div id="main">
							<ul>
								<li style="top: 12vh;" aos="fade-up" aos-anchor-placement="bottom-bottom"> 
									<img src="@/assets/images/yulin/travel_p1.png" alt="" style="width: 15vw;height:50vh" >
								   	<div class="info">
									   	<h1>玉林市智慧旅游建设情况</h1>
									  	<p>———旅游文化历史浓郁 </p>
									  	<a href="/yl_ctly1" target="_blank">详情</a>
								   </div>
								</li>
								<li aos="fade-up" aos-anchor-placement="bottom-bottom"> 
									<img src="@/assets/images/yulin/travel_p2.png" alt=""  style="width: 15vw;height:50vh">
								   <div class="info">
									<h1>玉林市智慧旅游建设情况</h1>
									  <p>———旅游市场客观需求</p>
									  <a href="/yl_ctly2" target="_blank" >详情</a>
								   </div>
								</li>
								<li aos="fade-up" aos-anchor-placement="bottom-bottom"> 
									<img src="@/assets/images/yulin/travel_p3.png" alt="" style="width: 15vw;height:50vh" >
								   <div class="info">
									<h1>玉林市智慧旅游建设情况</h1>
									  <p>———玉林智慧旅游发展三年行动计划</p>
									  <a href="/yl_ctly3" target="_blank" >详情</a>
								   </div>
								</li>
								<li style="top: 12vh;" aos="fade-up" aos-anchor-placement="bottom-bottom"> 
									<img src="@/assets/images/yulin/travel_p4.png" alt=""  style="width: 15vw;height:50vh" >
									<div class="info">
										<h1>玉林市智慧旅游建设情况</h1>
									   <p>———容县智慧侨乡建设（国家级特色旅游名县）</p>
									   <a href="/yl_ctly4" target="_blank" >详情</a>
									</div>
								 </li>
							</ul>
						 </div>
					</el-row>
					<el-row class="travel_module2">
						<div id="main" style="margin: auto">
							<ul>
								<li style="top: 12vh;" aos="fade-up" aos-anchor-placement="bottom-bottom">
									 <img src="@/assets/images/yulin/travel_p5.png" alt="" style="width: 15vw;height:50vh" >
								   <div class="info">
									<h1>玉林市智慧旅游建设情况</h1>
									  <p>———容县智慧旅游建设情况</p>
									  <a href="/yl_ctly5" target="_blank" >详情</a>
								   </div>
								</li>
								<li aos="fade-up" aos-anchor-placement="bottom-bottom"> 
									<img src="@/assets/images/yulin/travel_p6.png" alt="" style="width: 15vw;height:50vh" >
								   <div class="info">
									<h1>玉林市智慧旅游建设情况</h1>
									  <p>———市校双方共同推进项目</p>
									  <a href="/yl_ctly6" target="_blank">详情</a>
								   </div>
								</li>
								<li aos="fade-up" aos-anchor-placement="bottom-bottom"> 
									<img src="@/assets/images/yulin/travel_p7.png" alt=""  style="width: 15vw;height:50vh" >
								   <div class="info">
									<h1>玉林市智慧旅游建设情况</h1>
									  <p>———出具“玉林全域旅游大数据平台”方案</p>
									  <a href="/yl_ctly7" target="_blank" >详情</a>
								   </div>
								</li>
								<li style="top: 12vh;" aos="fade-up" aos-anchor-placement="bottom-bottom"> 
									<img src="@/assets/images/yulin/travel_p8.png" alt="" style="width: 15vw;height:50vh" >
									<div class="info">
										<h1>玉林市智慧旅游建设情况</h1>
									   <p>———项目建设进度</p>
									   <a href="/yl_ctly8" target="_blank" >详情</a>
									</div>
								 </li>
							</ul>
						 </div>
					</el-row>
                </div>
	   
		<!-- 数字玉林·大数据助力精准扶贫板块内容 -->
        <div id="box_fp" class="bk_fp">
            <el-row class="title_text" aos="zoom-in">
                数字玉林·大数据助力精准扶贫
			</el-row>
			<el-row >
				<div id="wrap" aos="flip-left">
				<ul >
					<li>
					<a href="" class="a1">
						<img src="@/assets/images/yulin/fp_p1.png">
						<div class ="divA">
							<p class="p1">玉林市博白民生资金大数据监督平台升级</p>
							<p class="p2">经过5个月的试运行，升级提档后的博白县民生资金大数据监督平台日前重新上线...</p>
						</div>
					</a>
					<a class = "a2"  href="/yl_ctfp1" target="_blank">
							<p class="p4">玉林市博白民生资金大数据监督平台升级</p>
							<p class="p5">经过5个月的试运行，升级提档后的博白县民生资金<br>大数据监督平台日前重新上线...</p>
							<p class="p7">查看详情></p>
					</a>
				</li>
				<li>
					<a href="" class="a1">
						<img src="@/assets/images/yulin/fp_p2.jpg">
						<div class ="divA">
							<p class="p1">玉林市大数据精准助力贫困学子上学</p>
							<p class="p2">为实现教育精准资助，切实保障建档立卡贫困户学生资助“一个不漏”，我市建立了“市—县—乡（镇）—校”四级联动...</p>
						</div>
					</a>
					<a class = "a2" href="/yl_ctfp2" target="_blank">
							<p class="p4">玉林市大数据精准助力贫困学子上学</p>
							<p class="p5">为实现教育精准资助，切实保障建档立卡贫困户学生<br>资助“一个不漏”，我市建立了“市—县—乡（镇）—校”四级联动...</p>
							<p class="p7">查看详情></p>
					</a>
				</li>
				<li>
					<a href="" class="a1">
						<img src="@/assets/images/yulin/fp_p3.jpg">
						<div class ="divA">
							<p class="p1">玉林市博白县运用“大数据”盯住民生资金</p>
							<p class="p2">建立大数据平台进行数据比对，是博白县在广西首创民生资金电子动态监管平台的基础上...</p>
						</div>
					</a>
					<a class = "a2" href="/yl_ctfp3" target="_blank">
							<p class="p4">玉林市博白县运用“大数据”盯住民生资金</p>
							<p class="p5">建立大数据平台进行数据比对，是博白县在广西首创<br>民生资金电子动态监管平台的基础上...</p>
							<p class="p7">查看详情></p>
					</a>
				</li>
				<li>
					<a href="" class="a1">
						<img src="@/assets/images/yulin/fp_p4.jpg"/>
						<div class ="divA">
							<p class="p1">玉林市兴业县“扶贫云”大数据助力扶贫</p>
							<p class="p2">兴业县围绕“三盯三查”（盯政策落实、查不正之风，盯资金安全等专项行动，开发建立兴业县“扶贫云”大数据平台...</p>
						</div>
					</a>
					<a class = "a2" href="/yl_ctfp4" target="_blank">
							<p class="p4">玉林市兴业县“扶贫云”大数据助力扶贫</p>
							<p class="p5">兴业县围绕“三盯三查”（盯政策落实、查不正之风，<br>盯资金安全等专项行动，开发建立兴业县“扶贫云”大数据平台...</p>
							<p class="p7">查看详情></p>
					</a>
				</li>
				<li>
					<a href="" class="a1">
						<img src="@/assets/images/yulin/fp_p5.jpg"/>
						<div class ="divA">
							<p class="p1">玉林市陆川米场镇再练电商扶贫“硬招式”</p>
							<p class="p2">米场镇注重电商扶贫模式的推广，实施农村电商精准扶贫，促进贫困村农产品“上线上网”、畅通“农产品进城”</p>
						</div>
					</a>
					<a class = "a2" href="/yl_ctfp5" target="_blank">
							<p class="p4">玉林市陆川米场镇再练电商扶贫“硬招式”</p>
							<p class="p5">米场镇注重电商扶贫模式的推广，实施农村电商精准<br>扶贫，促进贫困村农产品“上线上网”、畅通“农产品进城”...</p>
							<p class="p7">查看详情></p>
					</a>
				</li>
				<li>
					<a href="" class="a1">
						<img src="@/assets/images/yulin/fp_p6.jpg">
						<div class ="divA">
							<p class="p1">玉林市博白县民生资金事前监督</p>
							<p class="p2">今年以来，博白县纪委监委为突破事前监督盲区的问题，对原有民生资金监督平台进行全面升级完善，运用最新的大数据技术，构建民生大数据监督平台</p>
						</div>
					</a>
					<a class = "a2" href="/yl_ctfp6" target="_blank">
							<p class="p4">玉林市博白县民生资金事前监督</p>
							<p class="p5">今年以来，博白县纪委监委为突破事前监督盲区的问<br>题，对原有民生资金监督平台进行全面升级完善，运用最新的大数据技术...</p>
							<p class="p7">查看详情></p>
					</a>
				</li>
			</ul>
		</div>
	</el-row>
		</div>

		<!-- 数字玉林·扶持地方特色产业板块内容 -->
		<div id="box_cy" class="bk_cy">
		<!-- <div id="yl_particles-js" style="display: flex;align-items: center;justify-content: center"></div> -->
            <el-row class="title_text" aos="zoom-in">
                数字玉林·扶持地方特色产业
			</el-row>
			<el-row class="chanye">
				<el-col style="width: 55vw;height: 100%;margin: 8vh 0vw 0vh 0vw;left: 0vw;" aos="zoom-in-right">
					<div id="container">
						<div id="itemlist" style="margin-left: 12vw;" >
							<img src="@/assets/images/yulin/chanye_p1.jpg" alt="Busby" id="busby" style="width: 40vw;height: 55vh; border:0.5vw solid rgb(253, 251, 252);background-size: 35vw 25vw;">
							<img src="@/assets/images/yulin/chanye_p3.jpg" alt="Gridly" id="gridly" style="width: 40vw;height: 55vh; border:0.5vw solid rgb(253, 251, 252);background-size: 35vw 25vw;">
							<img src="@/assets/images/yulin/chanye_p6.jpg" alt="Reco" id="reco" style="width: 40vw;height: 55vh; border:0.5vw solid rgb(253, 251, 252);background-size: 35vw 25vw;">
							<img src="@/assets/images/yulin/chanye_p4.jpg" alt="Theblog" id="theblog" style="width: 40vw;height: 55vh; border:0.5vw solid rgb(253, 251, 252);background-size: 35vw 25vw;">
						</div>
					</div>  
				</el-col>				
				<el-col style="width: 35vw;height: 100%;margin: 3vh 2.5vw 0vh 0vh;" aos="zoom-in-left">
					<div id="container" style="width: 35vw; margin-bottom: 4vh;overflow-y:auto;background-color:aliceblue; border: 1vh solid rgb(158, 163, 165); ">
						<div id="itemdescription">
							<span data-for="busby">
								<p style="color: #000;text-align: center;font-size: 4vh;line-height: 6vh; margin-top: 2vh;">玉林：大数据开启智慧农业新时代</p>
								<p style="margin-top: 2vh;line-height: 4.25vh;font-size: 2.5vh;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;大数据开启智慧农业新时代,玉林市已建成5个县级运营中心、1078个标准站，信息进村入户走上“高速路”。人们用手指轻点鼠标，就能看到每一棵黄金桔的即时模样，还有现场温度、湿度、二氧化碳浓度等；只需“扫一扫”包装上的二维码，就能准确了解农产品从生产、加工、流通、仓储到销售等全过程的信息……这是在兴业凤鸣雅江生态种养（核心）示范区智慧农业体验厅体验到的“智慧农业”。</p>
								<p style="line-height: 4.25vh;font-size: 2.5vh;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;近年来，我市着力推动“互联网+农业”现代信息技术与农业生产、经营、管理、服务各环节和农村经济社会各领域的深度融合，大力发展智慧农业，引领农业现代化加快发展，为乡村振兴战略的实施注入了强劲活力。</p>
								<br>
								<br>
							</span>
							<span data-for="gridly">
								<p style="color: #000;text-align: center;font-size: 4vh;line-height: 6vh; margin-top: 2vh;">借力“互联网+”,玉林中药港力建“大数据”</p>
								<p style="line-height: 4.25vh;font-size: 2.5vh;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;纵观玉林中药材市场的发展，玉林市中药材市场建立至今已26个年头！玉林中药材的交易，由上个世纪80年代在火车站附近一带的中药材圩市，到1988年的玉林市中药材市场应势建成并投入使用，再到如今玉林银丰国际中药港这个现代化中药材综合市场。步伐是从圩场走进城区，从地摊走进商铺，而交易额也是在逐年递增，如今，玉林中药材市场已成为我国华南和中南地区规模最大的中药材集散地和批发市场，中药材远销国内外，每年来玉林进行药材交易的外地商家更是不计其数。</p>
								<p style="line-height: 4.25vh;font-size: 2.5vh;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;当下，借助互联网信息技术，通过收集搭建的数据库，这个数据库初步作用就是建立起类似图书馆搜索器一样，药商前来中药港选购药材时，只需在搜索器上输入想找的药材，轻松地搜索有所需品种出售的店铺。通过这样的标准化供求信息，一举打破以往中药材分散的“地摊式”经营模式，买家和卖家可以十分轻松地搜索配对，促成交易。</p>
								<br>
								<br>
							</span>
							<span data-for="reco">
								<p style="color: #000;text-align: center;font-size: 4vh;line-height: 6vh; margin-top: 2vh;">北流力建农特优产品大数据</p>
								<p style="margin-top: 2vh;line-height: 4.25vh;font-size: 2.5vh;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;4日上午，北流市县域互联网+溯源体系+精准扶贫项目启动仪式在北流市政府举行。北流市将建立特色农产品质量安全监管、溯源体系，建立“生产可记录、安全可预警、源头可追溯、流向可跟踪、信息可存储、身份可查询、责任可认定、产品可召回”的智能化质量安全监管和大数据云平台。</p>
								<p style="line-height: 4.25vh;font-size: 2.5vh;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;相关负责人表示，销售的产品所有扫码记录留下的相关信息都可以通过后台大数据进行分析，为精准营销提供参考。大数据除了能大大提高本地企业和农户对市场的预判能力，促进产业机构调整之外，消费者还可以通过扫码了解北流农产品的同时，了解到北流的投资环境、民俗文化、美食、旅游等信息，有利于宣传北流，提高北流的知名度。</p>
								<p style="line-height: 4.25vh;font-size: 2.5vh;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;通过此次合作，北流优质产品将进一步打开全国销售通道，实现农产品和经营者与互联网结合转型的升级，进一步促进农业增效、农民增收。</p>
								<br>
								<br>
							</span>
							<span data-for="theblog">
								<p style="color: #000;text-align: center;font-size: 4vh;line-height: 6vh; margin-top: 2vh;">“电商+扶贫” 百香果农有盼头</p>
								<p style="margin-top: 2vh;line-height: 4.25vh;font-size: 2.5vh;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;近年来，北流市努力把百香果产业作为地方特色产业、新兴产业和优势产业，不断做强、做大。百香果先后为北流捧回了“中国百香果之乡”“中华名果”“中国消费者最喜爱（水果）原产地”等国字号招牌。小小百香果托起了北流的“大产业”。</p>
								<p style="line-height: 4.25vh;font-size: 2.5vh;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;据统计，目前北流市建成上规模的果汁、饮料加工企业4家，年生产果汁、饮料等产品2万多吨，百香果深加工产品包括果汁、果浆、果脯、果冻等10多种；物流快递企业54家，生产包装保鲜材料用品的企业6家。去年，北流电商百香果销售量占全国的70%，份额全国第一。今年，北流电商借助“百香果电商文化旅游节”“广西特产行销全国”等活动，进一步拓宽百香果的销售范围和销售渠道。根据北流市各快递公司统计，2018年从北流发出的百香果快件量已超1000万件，北流百香果的网上销售量占据了全国76%的网销份额，北流已经成为中国最大的百香果集散地。</p>
								<br>
								<br>
							</span>
						</div>
					</div>  
				</el-col >	
			</el-row>
		</div>
		</div>
			<!-- <script src="js/yl_particles.js"></script>
			<script src="js/yl_app.js"></script> -->
			
    </div>
</template>

<script>
    export default{
		data(){
			return{
				cs_dialog1:false,
				cs_dialog2:false,
				cs_dialog3:false,
				cs_dialog4:false,
				cs_dialog5:false,
				cs_dialog6:false,
				// 政务服务
				zw_click:0,
			}
		},
        head:{
            script:[
            {src:'js/jquery.1.7.1.min.js'},
			{src:'js/aos.js'},
			{src:'scripts/yl_app.js'},

			// 城市建设模块
			{src:'js/yl_jquery.min.js'},
			{src:'js/jquery-1.12.4.min.js'},
			{src:'js/popper.min.js'},

			// 政务服务板块
			// {src:'js/yl_b.js'},
			// {src:'js/react.production.min.js'},
			// {src:'js/react-dom.production.min.js'},
			// {src:'js/index.js'},

			// 产业模块
			{src:'js/yl_chanye/jquery-1.7.2.min.js'},
			{src:'js/yl_chanye/modernizr.custom.34807.js'},
			{src:'js/yl_chanye/demo.js'},

			// 产业模块背景动画效果
			// {src:'js/yl_app.js'},
			// {src:'js/yl_particles.js'},
        ],
        link: [
            { rel: 'stylesheet', href: 'js/aos.css' },
            { rel: 'stylesheet', href: 'styles/yl_main.css' },
            { rel: 'stylesheet', href: 'css/normalize.css' },
            { rel: 'stylesheet', href: 'css/demo.css' },
			{ rel: 'stylesheet', href: 'css/styles.css' },
			
			// 城市建设模块
			{ rel: 'stylesheet', href: 'css/yl_citystyle.css' },

            { rel: 'stylesheet', href: 'css/miktu.css' },
            { rel: 'stylesheet', href: 'css/page-style.css' },

			// 产业模块
			{ rel: 'stylesheet', href: 'css/yl_style.css' },
			{ rel: 'stylesheet', href: 'css/style_cy.css' },

			// 产业模块背景动画
			// { rel: 'stylesheet', href: 'css/yl_login.css' },
		
			// 扶贫模块
			{ rel: 'stylesheet', href: 'css/yl_demo.css' },

        ]
		},
    methods: {
    handleScroll() {
        let top = pageYOffset || document.documentElement.scrollTop || document.body.scrollTop;
        if(top > 250){
            this.isFixed = 1;
        }else if(top < 200){
            this.isFixed = 0;
        }
    },
    handleAnimate() {
        let top = pageYOffset || document.documentElement.scrollTop || document.body.scrollTop;
        let vh = document.documentElement.clientHeight;
        let dom = document.querySelectorAll(".animate");
        [].slice.call(dom).forEach(v => {
            if(top + vh > v.offsetTop){
                var delay = v.dataset.delay;
                if(delay){
                    setTimeout(() => {
                        v.style.opacity = 1;
                        v.classList.add(v.dataset.ani)
                    }, delay)
                }else{
                    v.style.opacity = 1;
                    v.classList.add(v.dataset.ani)
                }
            }else{
                v.classList.remove(v.dataset.ani)
                v.style.opacity = 0;
            }
        })

        },
        nav(idx){
            this.nav_lock = idx
        },
		// 城市模块
	city(){
		$(function(){
			$('#accordion > li').hover(function(){
				var $this = $(this);
				$this.stop().animate({'width':'480px'},500);
				$('.heading',$this).stop(true,true).fadeOut();
				$('.bgDescription',$this).stop(true,true).slideDown(500);
				$('.description',$this).stop(true,true).fadeIn();
			},function(){
				var $this = $(this);
				$this.stop().animate({'width':'115px'},1000);
				$('.heading',$this).stop(true,true).fadeIn();
				$('.description',$this).stop(true,true).fadeOut(500);
				$('.bgDescription',$this).stop(true,true).slideUp(700);
			});

		});
	},
	// 扶贫板块方法
	fp(){
		$('li').mouseenter(function(){
			$(this).find('.divA').stop().animate({bottom:'-66px'});
			$(this).find('.a2').css({left:'0'})
			$(this).children('.a2').find('.p4').css({left:'0'})
			$(this).children('.a2').find('.p5').css({left:'0'})
			$(this).children('.a2').find('.p6').css({transform:'scale(1)'})
			$(this).children('.a2').find('.p7').css({bottom:'25px'})
		})
		$('li').mouseleave(function(){
			$(this).find('.divA').stop().animate({bottom:'0px'});
			$(this).find('.a2').css({left:-$(this).width()})
			$(this).children('.a2').find('.p4').css({left:-$(this).width()})
			$(this).children('.a2').find('.p5').css({left:-$(this).width()})
			$(this).children('.a2').find('.p6').css({transform:'scale(1.3)'})
			$(this).children('.a2').find('.p7').css({bottom:'-50px'})
		})
	},
	close_video(){
        var myVideo=document.getElementById("video1");
        myVideo.pause();
    },
},
    mounted() {
    AOS.init({
        easing: 'ease-out-back',
        duration: 500,
		// delay:500
    });
    this.$nextTick(() => {
        this.handleAnimate()//初始化第一次加载时在视口内就执行动画
        addEventListener('scroll', this.handleScroll);
        addEventListener('scroll', this.handleAnimate);

    });
	this.city();
	this.fp();
    
    },
    destroyed() {
    removeEventListener('scroll', this.handleScroll);//避免影响其他页面
    removeEventListener('scroll', this.handleAnimate);
    },
    
    
}
</script>


<style>
	@import "@/assets/css/yulin/yl_body.css";
</style>