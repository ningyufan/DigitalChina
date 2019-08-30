<template>
    <div>
        <div class="bk_cs">
            <el-row class="title_text">
                数字玉林·智慧城市建设
			</el-row>
			<el-row style="width: 100vw;height: 80vh;top: 7vh;" >
				<div id="content" aos="flip-up">
					<!--特效部分-->
					<ul class="accordion" id="accordion">
						<li class="bg1" >
							<div class="heading">玉林"智慧人大"平台</div>
							<div class="bgDescription"></div>
							<div class="description" >
								<h2>玉林"智慧人大"平台</h2>
								<p>玉林“智慧人大”管理平台包括电脑端（PC）和手机客户端（APP端），主要有“立法系统”、“监督系统”、“代表履职系统”、“办公系统”、“信息系统”等5大功能系统、30多个子系统。通过该系统，将使人大机关办公更加便捷、高效，立法、监督等各项职能实现“互联网+”，代表履职管理和议案、建议办理“一键通”...</p>
								<a @click="cs_dialog1 = true">更多 &rarr;</a>
							</div>
						</li> 
						<li class="bg2">
							<div class="heading">玉林城市普惠平台</div>
							<div class="bgDescription"></div>
							<div class="description">
								<h2>玉林城市普惠平台</h2>
								<p>玉林市总工会、玉林市区农村信用合作联社以及广西金拇指网络科技信息有限公司联合创新打造了一个“银行+智慧城市商家联盟+工会会员”普惠化服务平台，平台通过建成一张融合工会服务、商业服务、金融服务、互联网服务等主要功能的“广西（玉林）工会会员服务卡”，扩大工会会员的享受服务范围...</p>
								<a @click="cs_dialog2 = true">更多 &rarr;</a>
							</div>
						</li> 
						<li class="bg3">
							<div class="heading">发力数字玉林建设</div>
							<div class="bgDescription"></div>
							<div class="description">
								<h2>发力数字玉林建设</h2>
								<p>在当前“深入实施大数据战略加快数字广西建设”的大潮中，中国电信玉林分公司在现有全光网络的基础上，进一步加大投入、升级网络能力，大力打造高速宽带精品网络，进一步提升玉林信息通信基础设施能力，为“数字广西”建设提供强大的支撑...</p>
								<a @click="cs_dialog3 = true">更多 &rarr;</a>
							</div>
						</li>
						<li class="bg4">
							<div class="heading">玉林市大数据研究院</div>
							<div class="bgDescription"></div>
							<div class="description">
								<h2>玉林市大数据研究院</h2>
								<p>以玉林市大数据中心、玉林师范学院大数据应用创新中心、广西高校复杂系统优化与大数据处理重点实验室为依托，把玉林市大数据研究院建成一个面向全市乃至全区的行业大数据研究机构，为全市及全区的大数据产业发展提供技术支撑和服务，形成利用科研能力提供行业服务，利用行业服务实现人才培养，利用人才培养支撑科研能力建设的良性循环...</p>
								<a @click="cs_dialog4 = true">更多 &rarr;</a>
							</div>
						</li>
						<li class="bg5">
							<div class="heading">“智慧玉林”签约启动</div>
							<div class="bgDescription"></div>
							<div class="description">
								<h2>“智慧玉林”签约启动</h2>
								<p>2016年11月7日，玉林市智慧城市建设座谈会暨签约仪式在南宁举行，玉林市政府与曙光云计算有限公司就玉林市智慧城市建设项目进行签约，标志着“智慧玉林”项目正式启动和实施。市长苏海棠，副市长李振品，曙光信息产业股份有限公司董事、高级副总裁，曙光云计算有限公司总裁聂华出席签约仪式...</p>
								<a @click="cs_dialog5 = true">更多 &rarr;</a>
							</div>
						</li>
						<li class="bg6 bleft">
							<div class="heading">入选“国家智慧城市”</div>
							<div class="bgDescription"></div>
							<div class="description">
								<h2>入选“国家智慧城市”</h2>
								<p>2015年4月，玉林市入选国家智慧城市试点。创建智慧城市活动，是玉林市“三个年一活动”的重要内容和有力载体，在前期工作的基础上，目前创建工作进入顶层设计阶段，将稳步实施16个项目，力争用3年至5年创成国家智慧城市...</p>
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
					center>
					<span>
						<div class="dialog-video1">
							<video src="@/assets/video/yl_video1.mp4" controls="controls" autoplay="autoplay" width="74%" height="25%"></video>
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
					title="玉林市智慧城市建设座谈会暨签约仪式在南宁举行“智慧玉林”项目正式启动"
					:visible.sync="cs_dialog5"
					width="60%"
					center>
					<span>
						<div class="dialog-img">
							<img src="@/static/images/city_p5.png"  width="70%" height="30%" >
						</div>
						<br>
						<div class="font-content">
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;11月7日，玉林市智慧城市建设座谈会暨签约仪式在南宁举行，玉林市政府与曙光云计算有限公司就玉林市智慧城市建设项目进行签约，标志着“智慧玉林”项目正式启动和实施。市长苏海棠，副市长李振品，曙光信息产业股份有限公司董事、高级副总裁，曙光云计算有限公司总裁聂华出席签约仪式。</p>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;苏海棠对聂华一行的到来表示感谢，并向他们汇报了玉林的经济社会发展情况，尤其是城市信息化建设情况。他说，“智慧城市”是城市信息化发展的高级阶段，是对城市管理、公共服务、民生保障、商务活动等多种城市需求的智能化响应，对于改进政府管理、提升居民生活质量具有重要意义。近年来，我市高度重视城市信息化建设，在电子政务、信息网络建设等方面取得了显著成绩，为玉林市“智慧城市”建设奠定了较好的基础。这次签约的玉林市“智慧城市”建设项目包括智慧政务综合平台、智慧社区、智慧园区、智慧药都等19个项目，我们将按照“整体规划、分步实施”的原则予以推进，项目建成后，必将对城市智能化管理、政府科学决策、特色产业发展产生极大的促进作用。在今后的建设中，恳切希望广西中科曙光云计算有限公司（中科曙光）充分发挥技术和资源优势，全力投身项目建设，确保将玉林市“智慧城市”建设项目打造成“智慧城市”建设的样板工程。</p>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;听取汇报后，聂华表示对玉林经济社会发展所取得的成绩感到高兴，同时为能够参与玉林市的“智慧城市”建设感到荣幸。今后，中科曙光将以最好的技术、最大的力量投入项目建设，与玉林市政府共同谱写“让玉林更智慧、让生活更幸福”的“智慧玉林”新篇章。</p>
						</div>
					</span>
				</el-dialog>
				<el-dialog
					title="玉林市入选国家智慧城市 "
					:visible.sync="cs_dialog6"
					width="60%"
					center>
					<span>
						<div class="dialog-img">
							<img src="@/static/images/city_p6.png"  width="50%" height="30%">
						</div>
						<br>
						<div class="font-content">
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2015年4月，我市入选国家智慧城市试点。创建智慧城市活动，是玉林市“三个年一活动”的重要内容和有力载体，在前期工作的基础上，目前创建工作进入顶层设计阶段，将稳步实施16个项目，力争用3年至5年创成国家智慧城市。</p>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;我市创建国家智慧城市的目标主要是：通过创建智慧城市，智慧地推进玉林新型城镇化建设，全面提高城市规划建设科学性、城市管理高效精细化、完善公共服务、改善民生，促进产业转型升级，全面促进经济社会发展，形成智慧城市管理、幸福民生、产业转型升级框架；信息化全面支撑玉林经济社会快速、持续发展，城市运行状态全面可视化，城市安全实现全方位预防可控，城市运行管理决策实现有效支撑；民生得到进一步改善，社会公共服务实现均等便捷化发展，人民群众生活幸福感倍增，建成服务型政府；经济实现转型升级良性发展，基本建成智慧化的北部湾中心城市。</p>
						</div>
					</span>
				</el-dialog>
            </el-row> 
		</div>
		
		<!-- 数字玉林·“互联网+”政务服务板块 -->
        <div class="bk_zw">
            <el-row class="title_text">数字玉林·“互联网+”政务服务</el-row>
			<el-row class="zhengwu_module1" aos="fade-up">1</el-row>
			<el-row class="zhengwu_module2" aos="flip-right">
				<el-col class="zhengwu_module2_1" >
					<div class="bs-example" style="background-color: transparent;border: 0;" >
						<div class="row"  style="top: 2vh;">
							<div class="col-sm-6">
								<div class="ih-item square effect3 bottom_to_top"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
									<a href="#">
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
				</el-col>
				<el-col class="zhengwu_module2_1">
					<div class="bs-example" style="background-color: transparent;border: 0;" >
						<div class="row"  style="top: 2vh;">
							<div class="col-sm-6">
								<div class="ih-item square effect3 bottom_to_top"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
									<a href="#">
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
				</el-col>
				<el-col class="zhengwu_module2_1">
					<div class="bs-example" style="background-color: transparent;border: 0;" >
						<div class="row"  style="top: 2vh;">
							<div class="col-sm-6">
								<div class="ih-item square effect3 bottom_to_top"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
									<a href="#">
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
				</el-col>
				<el-col class="zhengwu_module2_1">
					<div class="bs-example" style="background-color: transparent;border: 0;" >
						<div class="row">
							<div class="col-sm-6">
								<div class="ih-item square effect3 bottom_to_top"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
									<a href="#">
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
				</el-col> 

			</el-row>
		
		</div>
			<div class="bk_ly">
                    <el-row class="title_text">
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
       
        <div class="bk_fp">
            <el-row class="title_text">
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
							<!-- <p class="p3">¥<span>6999</span>起</p> -->
						</div>
					</a>
					<a class = "a2"  href="/yl_ctfp1" target="_blank">
							<p class="p4">玉林市博白民生资金大数据监督平台升级</p>
							<p class="p5">经过5个月的试运行，升级提档后的博白县民生资金<br>大数据监督平台日前重新上线...</p>
							<!-- <p class="p6">¥<span>6999</span>起</p> -->
							<p class="p7">查看详情</p>
					</a>
				</li>
				<li>
					<a href="" class="a1">
						<img src="@/assets/images/yulin/fp_p2.jpg">
						<div class ="divA">
							<p class="p1">玉林市大数据精准助力贫困学子上学</p>
							<p class="p2">为实现教育精准资助，切实保障建档立卡贫困户学生资助“一个不漏”，我市建立了“市—县—乡（镇）—校”四级联动...</p>
							<!-- <p class="p3">¥<span>6999</span>起</p> -->
						</div>
					</a>
					<a class = "a2" href="/yl_ctfp2" target="_blank">
							<p class="p4">玉林市大数据精准助力贫困学子上学</p>
							<p class="p5">为实现教育精准资助，切实保障建档立卡贫困户学生<br>资助“一个不漏”，我市建立了“市—县—乡（镇）—校”四级联动...</p>
							<!-- <p class="p6">¥<span>6999</span>起</p> -->
							<p class="p7">查看详情></p>
					</a>
				</li>
				<li>
					<a href="" class="a1">
						<img src="@/assets/images/yulin/fp_p3.jpg">
						<div class ="divA">
							<p class="p1">玉林市博白县运用“大数据”盯住民生资金</p>
							<p class="p2">建立大数据平台进行数据比对，是博白县在广西首创民生资金电子动态监管平台的基础上...</p>
							<!-- <p class="p3">¥<span>8399</span>起</p> -->
						</div>
					</a>
					<a href="" class = "a2" href="/yl_ctfp3" target="_blank">
							<p class="p4">玉林市博白县运用“大数据”盯住民生资金</p>
							<p class="p5">建立大数据平台进行数据比对，是博白县在广西首创<br>民生资金电子动态监管平台的基础上...</p>
							<!-- <p class="p6">¥<span>8399</span>起</p> -->
							<p class="p7">查看详情></p>
					</a>
				</li>
				<li>
					<a href="" class="a1">
						<img src="@/assets/images/yulin/fp_p4.jpg"/>
						<div class ="divA">
							<p class="p1">玉林市兴业县“扶贫云”大数据助力扶贫</p>
							<p class="p2">兴业县围绕“三盯三查”（盯政策落实、查不正之风，盯资金安全等专项行动，开发建立兴业县“扶贫云”大数据平台...</p>
							<!-- <p class="p3">¥<span>8499</span>起</p> -->
						</div>
					</a>
					<a href="" class = "a2" href="/yl_ctfp4" target="_blank">
							<p class="p4">玉林市兴业县“扶贫云”大数据助力扶贫</p>
							<p class="p5">兴业县围绕“三盯三查”（盯政策落实、查不正之风，<br>盯资金安全等专项行动，开发建立兴业县“扶贫云”大数据平台...</p>
							<!-- <p class="p6">¥<span>8499</span>起</p> -->
							<p class="p7">查看详情></p>
					</a>
				</li>
				<li>
					<a href="" class="a1">
						<img src="@/assets/images/yulin/fp_p5.jpg"/>
						<div class ="divA">
							<p class="p1">玉林市陆川米场镇再练电商扶贫“硬招式”</p>
							<p class="p2">米场镇注重电商扶贫模式的推广，实施农村电商精准扶贫，促进贫困村农产品“上线上网”、畅通“农产品进城”</p>
							<!-- <p class="p3">¥<span>2199</span>起</p> -->
						</div>
					</a>
					<a href="" class = "a2" href="/yl_ctfp5" target="_blank">
							<p class="p4">玉林市陆川米场镇再练电商扶贫“硬招式”</p>
							<p class="p5">米场镇注重电商扶贫模式的推广，实施农村电商精准<br>扶贫，促进贫困村农产品“上线上网”、畅通“农产品进城”...</p>
							<!-- <p class="p6">¥<span>2199</span>起</p> -->
							<p class="p7">查看详情></p>
					</a>
				</li>
				<li>
					<a href="" class="a1">
						<img src="@/assets/images/yulin/fp_p6.jpg">
						<div class ="divA">
							<p class="p1">玉林市博白县民生资金事前监督</p>
							<p class="p2">今年以来，博白县纪委监委为突破事前监督盲区的问题，对原有民生资金监督平台进行全面升级完善，运用最新的大数据技术，构建民生大数据监督平台</p>
							<!-- <p class="p3">¥<span>6999</span>起</p> -->
						</div>
					</a>
					<a href="" class = "a2" href="/yl_ctfp6" target="_blank">
							<p class="p4">玉林市博白县民生资金事前监督</p>
							<p class="p5">今年以来，博白县纪委监委为突破事前监督盲区的问<br>题，对原有民生资金监督平台进行全面升级完善，运用最新的大数据技术...</p>
							<!-- <p class="p6">¥<span>6999</span>起</p> -->
							<p class="p7">查看详情></p>
					</a>
				</li>
			</ul>
		</div>
	</el-row>
</div>
		<div class="bk_cy">
            <el-row class="title_text">
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
								<p style="color: #000;text-align: center;font-size: 3vh;font-weight: 550;margin-top: 2vh;">玉林：大数据开启智慧农业新时代</p>
								<p style="margin-top: 2vh;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;大数据开启智慧农业新时代,玉林市已建成5个县级运营中心、1078个标准站，信息进村入户走上“高速路”。人们用手指轻点鼠标，就能看到每一棵黄金桔的即时模样，还有现场温度、湿度、二氧化碳浓度等；只需“扫一扫”包装上的二维码，就能准确了解农产品从生产、加工、流通、仓储到销售等全过程的信息……这是在兴业凤鸣雅江生态种养（核心）示范区智慧农业体验厅体验到的“智慧农业”。</p>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;近年来，我市着力推动“互联网+农业”现代信息技术与农业生产、经营、管理、服务各环节和农村经济社会各领域的深度融合，大力发展智慧农业，引领农业现代化加快发展，为乡村振兴战略的实施注入了强劲活力。</p>
								<br>
								<p style="color: #000;font-size: 2vh;font-weight: 550;">建设数据管理平台 发展智慧农业</p>
								<br>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“运用农业遥感技术，使用卫星影像和无人机、GPS等设备，为陆川县绿丰桔红中药产业（核心）示范区提供规划服务；为陆川县温泉镇、马坡镇、良田镇的一万多亩土地流转提供航拍服务。完成玉州区中药材基地、特色农业基地、马铃薯基地等规模化产业项目调查确认……”利用低空影像、遥感等技术，打造农林业资源分布“一张图”，仅是我市发展智慧农业的一个个例。</p>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;目前，我市在《玉林市深入实施大数据战略加快数字玉林建设工作方案》中做了互联网、大数据、人工智能与农业、服务业深度融合的规划。建设农业农村数据管理平台，发展智慧农业。运用物联网、低空影像、遥感等技术，打造农林业资源分布“一张图”，强化数据基础支撑，提升农情评估、灾害预警、价格监测、产量预测、土地确权等智能化管理水平。</p>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;依托现代特色农业示范区，开展特色优势产业智能技术应用，重点在玉林市11个自治区级现代特色农业示范区优选水稻、药材、禽畜养殖、沙田柚等基地数字化建设，加快构建农产品质量安全信息追溯管理平台。推进智能化、自动化成套装备技术的集成应用，推动农业机械设备和生产设施智能化改造，实现节水灌溉、测土配方施肥、农机定位耕种、饲料精准投放、疾病自动诊断等智能化作业。到2020年，我市将在自治区级现代农业产业园率先实现物联网技术应用全覆盖。</p>
								<br>
								<p style="color: #000;font-size: 2vh;font-weight: 550;">信息进村入户 助推农业产业升级</p>
								<br>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在农产品流通方面，我市农业农村局积极构建农产品上行体系，创造农民持续增收新增长点，陆续在各县（市、区）开展了信息进村入户工程建设。</p>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;目前，玉林市5个项目县按照“一村三站”及有场所、有人员、有设备、有宽带、有网页、有持续运营能力的“六有”标准建设，并建设好运营中心、益农信息社信息服务体系，实现普通农户不出村、新型农业经营主体不出户就可享受便捷的信息服务和农产品上行服务。每个行政村建设标准站、专业站、简易站各一个，在玉林市建立市、县、村信息服务构架，与自治区互联，共同建成“四级”联动的信息服务架构，打通农村信息通道。同时，开通上线综合信息服务平台，整合涉农政务信息平台等多样化服务资源，使益农信息社成为服务“三农”的重要平台。</p>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;截至目前，全市7个项目县已建成5个县级运营中心（博白、陆川、兴业、容县、北流)、1078个标准站、1078个专业站、1078个简易站，共培训村级信息员1735人次，信息进村入户工作名列广西前茅。 (记者 周立华 通讯员 何万里）</p>
							</span>
							<span data-for="gridly">
								<p style="color: #000;text-align: center;font-size: 3vh;font-weight: 550;margin-top: 2vh;">借力“互联网+”,玉林中药港力建“大数据”</p>
								<p style="margin-top: 2vh;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;数据库建立后如图书馆搜索器一样，选购药材时，不用像以前一样要逛大半个市场去找药材，只需在搜索器上输入想找的药材，就能轻松地搜索有所需品种出售的店铺，买家和卖家可以十分轻松地搜索配对，寻找商机，促成交易。</p>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;供货品名：白芍，规格：无硫，产地：安徽，数量：大货，单价：协商”……这几天，玉林中药材行业商会的各位班子成员，每天都是早出晚归，拿着本子和笔在做一件“大事”：逐个“拜访”在中药材市场里经营药材的商户，对每个商户店里销售的药材品种进行一次“大普查”，而这些数据都会被仔细记录下来，等待“普查”工作完毕后，这些数据将会录入电脑，最终形成玉林市中药材市场的药材数据库。而这个数据库的建立，或许将会给玉林市中药材市场带来一场更大的发展机遇。</p>
								<br>
								<p style="color: #000;font-size: 2vh;font-weight: 550;">改变传统的销售模式</p>
								<br>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;纵观玉林中药材市场的发展，玉林市中药材市场建立至今已26个年头！玉林中药材的交易，由上个世纪80年代在火车站附近一带的中药材圩市，到1988年的玉林市中药材市场应势建成并投入使用，再到如今玉林银丰国际中药港这个现代化中药材综合市场。步伐是从圩场走进城区，从地摊走进商铺，而交易额也是在逐年递增，如今，玉林中药材市场已成为我国华南和中南地区规模最大的中药材集散地和批发市场，中药材远销国内外，每年来玉林进行药材交易的外地商家更是不计其数。</p>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;市场在变，交易在变，但经营方式还没有改变。中药材市场里的药商，大多仍是按照固有的“摆摊式”进行，开门等候顾客的上门，而外地客商来选购药材，也是要在市场里转半天才能找到想要的品种，假如要购买的品种较多，将很耗费时间。</p>
								<br>
								<p style="color: #000;font-size: 2vh;font-weight: 550;">借助“互联网+”破局</p>
								<br>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;传统销售模式的短板，一定程度上困扰着经营户和采购药材客商，而这也成为横跨在商会壮大发展路上的一道坎。面对这个困扰，商会成员几番开会讨论，大家提出为何不紧紧围绕国家提出的“互联网+”这个方向去破局。</p>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;借助互联网信息技术，通过收集搭建的数据库，这个数据库初步作用就是建立起类似图书馆搜索器一样，药商前来中药港选购药材时，不用像以前一样要逛大半个市场去找药材，只需在搜索器上输入想找的药材，就能十分轻松地搜索有所需品种出售的店铺，直奔“主题”即可。通过这样的标准化供求信息，一举打破以往中药材分散的“地摊式”经营模式，买家和卖家可以十分轻松地搜索配对，寻找商机，促成交易。</p>
								<br>
								<p style="color: #000;font-size: 2vh;font-weight: 550;">　大胆试水，加速推进“大数据时代”</p>
								<br>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 说做就做，商会的领导班子最终拍板，但毕竟隔行如隔山，他们选择了和一家网站合作。经过前期的准备工作，这几天他们开始对中药材市场里的药材经营户进行一次彻底地摸底收集数据，对每个商户店里销售的药材品种进行一次“大普查”。</p>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“收集初步的数据，建立数据库，提供商品选购快速索引功能，这只是我们设想的第一步。”据玉林市中药材市场党支部书记吴志英介绍，如今上至国家层面下至平民百姓，都在倡导走“互联网+”道路，这次商会尝试走这种模式，可以说是前所未有的大胆尝试，从设想建设到真正投入使用，中间肯定还会有很多波折和困难，但是建成后，将会给玉林市中药材市场带去不一样的改变。	</p>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; 除了最先开通的销售索引这一功能，伴随着移动互联网的迅猛发展，还会进一步开拓更多的功能，比如建立网站平台，在网上发布供求信息，广大药企药商可以在这上面查看最新市场资讯和供求信息，甚至将来开发电子商务交易平台，药商可以直接完成网上交易，而业务人员也可以依托自身掌握的信息和资源，在线下促成双方交易，更多的功能和便利，值得期待。 （记者　陶继军）	</p>
							</span>
							<span data-for="reco">
								<p style="color: #000;text-align: center;font-size: 3vh;font-weight: 550;margin-top: 2vh;">北流力建农特优产品大数据</p>
								<p style="margin-top: 2vh;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;玉林新闻网-玉林晚报讯 （记者 廖晓东） 4日上午，北流市县域互联网+溯源体系+精准扶贫项目启动仪式在北流市政府举行。北流市将建立特色农产品质量安全监管、溯源体系，建立“生产可记录、安全可预警、源头可追溯、流向可跟踪、信息可存储、身份可查询、责任可认定、产品可召回”的智能化质量安全监管和大数据云平台。</p>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;据介绍，北流市目前已建成一大批无公害、绿色、有机的农产品生产基地，培育了凉亭鸡、“荔宝牌”鸡嘴荔等一批广西名牌产品。“要把产品打出去，要建立跨区域品牌，必须健全制度，明确责任，做到质量可溯源，责任可追究。”北流市相关负责人表示， “溯源体系”的建立有助于提升北流本地农特优产品的质量，从而提升产品的竞争力。通过“溯源”工程，消费者可以扫码了解产品的有关信息，达到促进北流名特优农产品的销售，提升北流市产品溢价空间，实现企业增效和农民增收。</p>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;该负责人表示，销售的产品所有扫码记录留下的相关信息都可以通过后台大数据进行分析，为精准营销提供参考。大数据除了能大大提高本地企业和农户对市场的预判能力，促进产业机构调整之外，消费者还可以通过扫码了解北流农产品的同时，了解到北流的投资环境、民俗文化、美食、旅游等信息，有利于宣传北流，提高北流的知名度。</p>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;通过此次合作，北流优质产品将进一步打开全国销售通道，实现农产品和经营者与互联网结合转型的升级，进一步促进农业增效、农民增收。</p>
							</span>
							<span data-for="theblog">
								<p style="color: #000;text-align: center;font-size: 3vh;font-weight: 550;margin-top: 2vh;">“电商+扶贫” 百香果农有盼头</p>
								<p style="margin-top: 2vh;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;得天独厚的自然条件，孕育出了北流人的“致富果”——百香果。近年来，北流市努力把百香果产业作为地方特色产业、新兴产业和优势产业，不断做强、做大。百香果先后为北流捧回了“中国百香果之乡”“中华名果”“中国消费者最喜爱（水果）原产地”等国字号招牌。小小百香果托起了北流的“大产业”。</p>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;北流市种植百香果已有30年的历史，但早期百香果产业发展缓慢，随着百香果产业化进程的推进和更多老百姓对百香果的营养价值的认识，以及随着网络技术和物流行业的发展，最近几年，北流百香果产业得到了迅猛的发展，百香果种植面积达5333.33公顷，去年产量达12万多吨，销售收入4亿多元。从科研到育苗，到大规模种植，到产品收购，到电商网络营销，到果品深加工，北流百香果有了比较完整的产业链，越来越多的农户和创业者进入“甜蜜”的百香果事业，涉足百香果种植、电商销售、果汁加工、鲜榨果浆及物流、包装等行业，形成令人赞叹的“百香果创业群体”。</p>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;据统计，目前北流市建成上规模的果汁、饮料加工企业4家，年生产果汁、饮料等产品2万多吨，百香果深加工产品包括果汁、果浆、果脯、果冻等10多种；物流快递企业54家，生产包装保鲜材料用品的企业6家。去年，北流电商百香果销售量占全国的70%，份额全国第一。今年，北流电商借助“百香果电商文化旅游节”“广西特产行销全国”等活动，进一步拓宽百香果的销售范围和销售渠道。根据北流市各快递公司统计，2018年从北流发出的百香果快件量已超1000万件，北流百香果的网上销售量占据了全国76%的网销份额，北流已经成为中国最大的百香果集散地。北流东云果业公司总经理杨兴忠告诉记者，目前他们公司销量每天大概是2.5万公斤左右，同比有所增加，相信未来百香果还是非常受市场欢迎的。</p>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;百香果当年种植当年结果，当年亩产800~1000公斤，正常年亩产2000公斤以上，年亩收入万元以上，可连续收益10年左右，投资少、见效快、效益高。北流市各级政府和脱贫攻坚后盾单位把种植百香果作为主要扶贫产业，给贫困户赠送果苗和肥料，并给予技术扶持，寻找销路，帮助贫困户增加收入。近年来，数以万计的农户依靠种植百香果致富。北流醉香果业公司总经理谭军说，他们公司今年计划育苗1000万株，发展更多的种植户去种植，获得更多的百香果收成。</p>
								<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;为了打造北流百香果名优品牌，北流市目前正在着手建设万亩黄金百香果核心示范区，充分整合百香果资源，在新荣、民安两镇建设了333.33公顷优质高产高效百香果连片种植基地，并且以点带面建立起15个优质高产高效百香果示范点，围绕“打造百香果产业强市”的目标，加快推进百香果产业的转型升级，促进种植结构优化升级，提升种植效益。与此同时，北流依托“中国百香果之乡”等国字号品牌影响力，做好宣传推广，吸引更多的资金进入北流百香果等水果产业链的建设，逐步建成华南地区的水果生产加工中心，进一步做强百香果产业。(责任编辑：刘子扬)</p>
								
							</span>
						</div>
					</div>  
				</el-col >	
			</el-row>
			
            </div>
    </div>
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

				// 扶贫无限滚动框
				count:0,
			}
		},
        head:{
            script:[
            {src:'js/jquery.1.7.1.min.js'},
            {src:'js/aos.js'},
            {src:'scripts/yl_app.js'},
		
			// 城市模块
            // {src:'js/ScrollText.js'},
			{src:'js/yl_jquery.min.js'},

			{src:'js/jquery-1.12.4.min.js'},
			{src:'js/popper.min.js'},


			// {src:'js/bootstrap.min.js'},
			// 产业模块
			{src:'js/yl_chanye/jquery-1.7.2.min.js'},
			{src:'js/yl_chanye/modernizr.custom.34807.js'},
			{src:'js/yl_chanye/demo.js'},

			// 扶贫模块
			// {src:'js/yl_chanye/jquery-1.7.2.min.js'},

			
            
        ],
        link: [
            { rel: 'stylesheet', href: 'js/aos.css' },
            { rel: 'stylesheet', href: 'styles/yl_main.css' },
            // { rel: 'stylesheet', href: 'css/default.css' },
            { rel: 'stylesheet', href: 'css/normalize.css' },
            { rel: 'stylesheet', href: 'css/demo.css' },
			{ rel: 'stylesheet', href: 'css/styles.css' },
			
			// 城市建设模块
			// { rel: 'stylesheet', href: 'css/yl_chstyle.css' },
			{ rel: 'stylesheet', href: 'css/yl_citystyle.css' },



			// { rel: 'stylesheet', href: 'css/bootstrap.min.css' },
            { rel: 'stylesheet', href: 'css/miktu.css' },
            { rel: 'stylesheet', href: 'css/page-style.css' },

			// 产业模块
			{ rel: 'stylesheet', href: 'css/yl_chanye/style.css' },

			// 扶贫模块
			{ rel: 'stylesheet', href: 'css/yl_chanye/demo.css' },

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
	// 城市模块弹出框关闭
	dialogClose(done){
        this.$confirm('确认关闭？')
          .then(_ => {
            done();
          })
          .catch(_ => {});
	},
		// 扶贫模块
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
	// 扶贫无限滚动方法
	// load () {
    //     this.count += 2
    //   }
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