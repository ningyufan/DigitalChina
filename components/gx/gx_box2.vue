<template>
    <div class="gx_box2">
        <div class="tab" aos = "zoom-in">
				智慧旅游
			</div>
			<div class="box2_an"></div>
			<div class="view" aos = "zoom-in">
				<div class="pic_info">
					<template v-if="pic_index == 0">
						<div class="top">
							指尖上的旅游
						</div>
						<div class="box3_content">
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“使用手机就能完成景区线上购票、刷脸扫码入园、酒店智能入住、餐厅自助点餐、线上预约车位、支付停车费，
								实在是太方便了。”今年元旦假期到桂林旅游的四川游客张先生不停夸赞。</p>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2018年2月11日，旅游综合服务平台“一键游桂林·i游桂林”上线运行后受到广大游客青睐。该平台有智能线路、
								移动支付、电子发票、人脸识别、智能导游、诚信体系等功能设置，能实现“吃、住、行、游、购、娱”等要素和“商、养、学、闲、情、奇”等业态全覆盖，
								可为游客提供全程化、个性化智慧旅游服务。平台整合了全市旅游管理资源，政府可对旅游市场进行全天候、全方位、全过程监管，游客在桂林旅游更安心。
								据统计，2018年，桂林接待游客1.09亿人次，同比增长32.58%；实现旅游总消费1391.75亿元，同比增长43.22%。
							</p>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
								“我从南宁青秀山景区APP看到，春节期间，景区将举办大花蕙兰、蝴蝶兰等30余种兰花和各式盆栽展销活动，我计划和家人一同前往。”南宁市民黄先生说，
								以前去青秀山大都在闲逛，现在点开手机APP，可知悉景区举办的各种活动，可以查询景区门票销售情况、路线规划、客流情况等信息，非常方便。
							</p>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
								近年来，大新德天瀑布景区的智慧旅游建设日益成熟。游客可通过微信购票，手机直接扫码入园，也可在自助售取票一体机购票，停车场管理系统可对车牌拍照识别，
								无需取卡，游客还可通过手机查看车位剩余情况和车位引导详解等。
							</p>
						</div>
					</template>
					<template v-if="pic_index == 1">
						<div class="top">
							“天眼”下的管理
						</div>
						<div class="box3_content">
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;大数据时代，视频监控成为管理的重要手段之一。在桂林旅游应急指挥中心，
								墙上整齐排列着视频框，象山景区停车场、芦笛岩景区入口、漓江冠岩段、解放桥六匹马码头、
								尧山索道进出站口等重要监控点都在工作人员的眼皮底下，这就是桂林旅游景区视频监控“天眼”。
							</p><br/>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2014年揭晓的“中国智慧城市创新奖”，桂林市旅游景区视频监控“天眼”工程榜上有名，
								成为国内旅游业唯一获奖的工程。该“天眼”监控点覆盖了市区所有3A级以上景区和周边5县部分代表性景区，通过“天眼”，
								旅游管理部门可实时监测景区的人流、车流，核实游客反映和投诉的情况，及时做好防止拥堵、救援等工作。
							</p><br/>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;据了解，2016年10月，青秀山、王城、漓江、
								乐满地4个5A级景区和部分重点4A级景区视频监控信号已接入文化和旅游部监控平台，广西是首批完成对接的省区市之一。
							</p><br/>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
								2018年12月，广西旅游大数据平台顺利通过第三方组织的专家测评验收，完成省级平台与全区170个国家A级旅游景区的视频对接，
								其中接入4A级以上景区128个，接入景区总数量排在全国前列。
							</p><br/>
						</div>
					</template>
					<template v-if="pic_index == 2">
						<div class="top">
							直通车式的平台
						</div>
						<div class="box3_content">
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
								“广西游直通车”平台涵盖住宿、餐饮、购物、娱乐、交通等综合信息服务体系，目前已完成包括共享汽车分时租赁系统、公务车管理系统、新能源汽车充电模块、
								旅游线路模块、酒店管理系统、景区票务及分销管理等基础核心模块的开发运营。
							</p><br/>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;据了解，钦州市各景区与“广西游直通车”平台合作，依托钦州高铁旅游集散中心及三娘湾、五皇山等景区，
								投放一批新能源景区直通车，游客可在集散中心、景区之间实现异地租车还车，出高铁站就可方便驾驶新能源共享汽车到达景区。
							</p><br/>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
								去年国庆节期间，大量游客通过直通车系统购票、购物，使用智慧停车、共享汽车和共享观光车系统，有效缓解了景区拥堵、人手不足等问题，整个系统运营顺畅，
								为景区迈向智能化提供了坚实基础。”三娘湾景区相关负责人说。据了解，“广西直通车”平台将继续整合钦州市宾馆、饭店、休闲娱乐、特产等资源，
								与其他景区景点加快整合，为游客提供更全面、更快捷、体验性更高的旅游线路产品及服务。
							</p><br/>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
								目前“广西游直通车”平台已陆续接入全区422家A级景区、1800多家星级农家乐、200多家特色民宿、近3000座旅游厕所的相关数据，实现景区票务与住宿、餐饮、
								旅游特产、娱乐、文化演艺等周边旅游业态的线上融合，为游客提供更加丰富的旅游产品和服务。
							</p><br/>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
								据了解，2018年以来，百色市加大和携程旅游的合作，通过携程大数据分析，对点击百色的游客打上标记并筛选出来，同时，搭建线下服务点和通道，
								以“门店+小交通+X”为载体，为游客提供到百色旅游的一站式服务，打通游客到目的地景区、酒店、会场等的“最后一公里”，2018年12月，
								广西首家“到站游体验馆”在百色投入运营，得到游客广泛好评。
							</p><br/>
						</div>
					</template>
					<template v-if="pic_index == 3">
						<div class="top">
							“产学研”的支撑
						</div>
						<div class="box3_content">
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
								为了给广西旅游信息化项目提供权威的地理信息服务，广西旅游部门与自治区遥感测绘信息院合作，依托信息技术和地理信息技术，以基础地理信息为基础，
								整合各类旅游信息资源，实现以二维、三维地图为表现形式的地理信息和旅游信息的检索、浏览等服务，共建“广西旅游一张图”。据了解，该项目分为三期建设，
								2018年进行的一期建设任务，主要包括旅游电子地图服务软件系统建设等内容。目前，一期项目进展顺利，已于2018年底通过了专家评审，预计投入使用后，
								将初步实现面向旅游管理部门、涉旅企业和游客的旅游地理信息服务。
							</p><br/>
							<p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
								广西高校也纷纷加入智慧旅游建设大潮中。以南宁师范大学、广西教育学院牵头的，多家单位共同承担的广西创新驱动重大项目《全域数字文化旅游智能服务技术研发及应用》，
								致力于用科技手段挖掘、提炼和展示广西文化，通过“文化+旅游+科技”，打造特色旅游品牌，促进广西全域旅游发展。目前项目方与广西中新正大国际旅游有限公司合作，
								已经完成柳州三江侗族自治县丹洲岛旅游文化知识图谱构建，即将完成丹洲岛风景区的网络展示。广西骆越文化整理和挖掘重要成果——大型文学小说《骆越演义》成功出版，
								目前项目方正携手大明山景区，以骆越文化为基础构建知识图谱，以新媒体技术为手段，打造自然景点与骆越文化相融合的智慧旅游新产品。
							</p><br/>
						</div>
					</template>
				</div>
			</div>
			<div class="pic_list"  aos = "zoom-in" >
				<div @click="pic_index = 0">
					<img src="../../assets/images/gx/gxbox2_pic1.jpg" alt="">
				</div>
				<div @click="pic_index = 1">
					<img src="../../assets/images/gx/gxbox2_pic2.jpg" alt="">
				</div>
				<div @click="pic_index = 2">
					<img src="../../assets/images/gx/gxbox2_pic3.jpg" alt="">
				</div>
				<div @click="pic_index = 3" aos = "slide-left" >
					<img src="../../assets/images/gx/gxbox2_pic4.jpg" alt="">
				</div>
			</div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            pic_index:0,
        }
    }
}
</script>

<style>
.gx_box2 {
    width: 100vw;
    height: 100vh;
    background-image: url(../../assets/images/gx/bg3.jpg);
    background-size: 100% 100%; 
    position: relative;
}
.gx_box2 .tab {
    width: 100vw;
    height: 15vh;
    line-height: 15vh;
    text-align: center;
    font-size: 6vh;
    font-family: STXingkai;
    color: rgb(48, 189, 245);
    
}
.gx_box2 .tab:hover {
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
.gx_box2 .box2_an {
    height: 80vh;
    width: 80vh;
    position: absolute;
    right: 0;
    bottom: 0;
    background-image: url(../../assets/images/gx/quan2.png);
    background-size: 100% 100%;
    animation: clockwise 10s linear infinite;
}
@keyframes clockwise {
    from{
        transform: rotateZ(0deg)
    }
    to {
        transform: rotateZ(360deg)
    }
}

.gx_box2 .view {
    height: 60vh;
    width: 80vw;
    margin: 0 auto;
    background-color:rgba(255, 255, 255, 0.5);
    z-index: 2;
    position: absolute;
    right: 10vw;
    top: 15vh;
}

.gx_box2 .view .pic_info {
    height: 55vh;
    width: 70vw;
    margin-left: 5vw;
    /* background-color: #ccc; */
    float: left;
    overflow: auto;
}
.gx_box2 .view .pic_info .top{
    height: 8vh;
    width: 100%;
    line-height: 8vh;
    text-align: center;
    font-size: 4vh;
}
.gx_box2 .view .pic_info .box3_content p{
    font-size:2.5vh;
}
.gx_box2 .pic_list {
    height: 25vh;
    width: 80vw;
    margin: 0 auto;
    position: absolute;
    left: 10vw;
    bottom: 0;
    /* background-color: bisque; */
}
.gx_box2 .pic_list img {
    height: 100%;
    width: 100%;
}
.gx_box2 .pic_list div{
    width: 20vw;
    height: 19vh;
    background-color: blue;
    float: left;
    margin-top: 3vh;
    transform-style: preserve-3d;
    transform: perspective(800px) rotateY(-40deg);
    transition: all 500ms ease-in-out;
}
.gx_box2 .pic_list div:hover {
    transform: perspective(800px) rotateY(0deg);
    transform: scale(1.2,1.2)
}
</style>