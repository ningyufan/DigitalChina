<template>
    <div class="gx_box1">
        <div class="tab" aos = "zoom-in">
				Smart City
			</div>
			<div class="con"  aos = "zoom-in">
				<div class="pic_style" @click="gx_dialog1 = true">
					<div class="img1"><img src="../../assets/images/gx/gxmap.png"  height="100%" width="100%" alt=""></div>
					<div class="img2"><img src="../../assets/images/gx/e_gxmap1.png"  height="100%" width="100%" alt=""></div>
				</div>
				<div class="cspic_list">
					<div class="cspic_list1" @click="gx_dialog2 = true">
						<div class="img1"><img src="../../assets/images/gx/nanning.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/e_nanning1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list2" @click="gx_dialog3 = true">
						<div class="img1"><img src="../../assets/images/gx/liuzhou.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/e_liuzhou1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list3" @click="gx_dialog4 = true">
						<div class="img1"><img src="../../assets/images/gx/guilin.png"  height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/e_guilin1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list4" @click="gx_dialog5 = true">
						<div class="img1"><img src="../../assets/images/gx/guigang.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/e_guigang1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list5" @click="gx_dialog6 = true">
						<div class="img1"><img src="../../assets/images/gx/qinzhou.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/e_qinzhou1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list6" @click="gx_dialog7 = true">
						<div class="img1"><img src="../../assets/images/gx/yulin.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/e_yulin1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list7" @click="gx_dialog8 = true">
						<div class="img1"><img src="../../assets/images/gx/yufengqu.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/e_yufengqu1.png" height="100%" width="100%" alt=""></div>
					</div>
					<div class="cspic_list8" @click="gx_dialog9 = true">
						<div class="img1"><img src="../../assets/images/gx/luzhaixian.png" height="100%" width="100%" alt=""></div>
						<div class="img2"><img src="../../assets/images/gx/e_luzhaixian1.png" height="100%" width="100%" alt=""></div>
					</div>
				</div>
            </div>
            <el-dialog :visible.sync="gx_dialog1" width="60%">
                <template slot="title">
                    <div class="gx_diatitle">
                        Guangxi national smart city————Six cities, one district and one county
                    </div>
                </template>
                <span>
                    <div class="gxdia_info">
                        <img src="../../assets/images/gx/gxmap.png"  alt="">
                        <p>
                           The ministry of housing and urban-rural development and the ministry of science and technology jointly announced the third batch of national smart city pilot lists.
                            Qinzhou and yulin cities have become new national smart city pilot projects, and luzhai county has been included in liuzhou pilot project to expand its scope. 
                            So far, a total of 6 cities, 1 district and 1 county in guangxi have been selected as national smart city pilot.
                        </p>
                    </div>                    
                </span>
                <span slot="footer" class="dialog-footer">                    
                    <el-button type="primary" @click="gx_dialog1 = false">return</el-button>
                </span>
            </el-dialog>
            <el-dialog :visible.sync="gx_dialog2" width="60%">
                <template slot="title">
                    <div class="gx_diatitle">
                       Nanning————Peace green city, the vitality of Nanning
                    </div>
                </template>
                <span>
                    <div class="gxdia_info">
                        <img src="../../assets/images/gx/nanning.png"  alt="">
                        <p>
                            "Peace" as the core, supporting the municipal, emergency disposal, transportation, energy, 
                            environment and so on to make residents reached the requirements of comfortable, convenient, 
                            safe, quickening construction of geared to the needs of the regional information exchange center of the association of south-east Asian nations (asean), 
                            the wide use of Internet of things, cloud computing, such as a new generation of information technology, 
                            build the wisdom of the urban operating environment and the new urban form.
                        </p><br/>
                        <p>
                            Centering on the word "peace" and focusing on the construction of smart security and smart emergency response, 
                            a comprehensive unified platform for emergency warning and police handling will be built through platform integration and department coordination. 
                            Specifically, is through the city emergency linkage center, 110, 119, 120, 122, four platforms, to integrate the public security, traffic, fire control,
                             etc, at the same time with the city emergency management, and is closely related to citizens living in the water and electricity gas and other units to realize information integration and sharing,
                              improve the ability of public emergency response and fast response. Meanwhile, combined with the "green" of "green city",
                               citizens will live in a more livable ecological environment in the future through intelligent application.
                        </p><br/>
                        <p>
                            Created during the term of nanning will be in accordance with the security system and infrastructure, construction and livable "wisdom"
                             and "wisdom of management and service", "innovation" and other four categories, plans to carry out "one platform, one center, 
                             four libraries and ten projects (connecting, energy saving, green building, water, gas, underground pipeline and management, traffic, 
                             environmental protection, safety and emergency)" construction, total investment is expected to about 52.3 billion yuan.
                        </p><br/>
                        <p>
                            It is expected that by 2017, an intelligent information infrastructure covering the central urban area will be initially built to make residents' lives safer, more convenient, efficient and green, 
                            and finally achieve the goal of building a "safe and green city, vibrant nanning".
                        </p><br/>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">                    
                    <el-button type="primary" @click="gx_dialog2 = false">return</el-button>
                </span>
            </el-dialog>
            <el-dialog :visible.sync="gx_dialog3" width="60%">
                <template slot="title">
                    <div class="gx_diatitle">
                        LiuZhou
                    </div>
                </template>
                <span>
                    <div class="gxdia_info">
                        <img src="../../assets/images/gx/liuzhou.png" alt="">
                        <p>
                            We will give full play to industrial advantages and resources, and establish a unified public information platform and information resource sharing service system. 
                            To achieve the development goals of saving, smart, green and low-carbon cities.
                        </p><br/>
                        <p>
                            In the pilot phase, liuzhou city plans to implement 24 key projects of "smart city" construction according to the four categories of "information infrastructure construction", 
                            "construction and livability", "management and service" and "innovation project", with a total investment of 12.56 billion yuan.
                        </p><br/>
                        <p>
                            It is expected that by 2018, a wide range of smart applications in the fields of e-government, e-commerce and electronic services will be basically realized, 
                            a number of key demonstration projects and smart industrial bases will be built, a basic framework for the development of "smart liuzhou" will be formed, 
                            and a smart industrial and ecological livable city will be created.
                        </p><br/>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">                    
                    <el-button type="primary" @click="gx_dialog3 = false">return</el-button>
                </span>
            </el-dialog>
            <el-dialog :visible.sync="gx_dialog4" width="60%">
                <template slot="title">
                    <div class="gx_diatitle">
                        GiuLin
                    </div>
                </template>
                <span>
                    <div class="gxdia_info">
                        <img src="../../assets/images/gx/guilin.png" alt="">
                        <p>
                            Take "smart tourism" as the breakthrough point of smart city construction and the growth point of information industry, 
                            drive the development of smart agriculture, smart transportation and a series of smart industries, 
                            and gradually complete the information construction of the whole smart city of guilin.
                        </p><br/>
                        <p>
                            In the next few years, based on the overall positioning of "creating a smart city with guilin characteristics",
                            guilin will further accelerate the pace of network infrastructure construction and promote the integration of telecommunication network, 
                            computer network and radio power grid. Build a unified "smart guilin" e-government network, build guilin cloud computing center, 
                            improve basic information database, build geographic information sharing platform, and build guilin information resource center; 
                            Improve the information security system. It is expected that by 2017, the basic framework of "smart guilin" will take shape, 
                            providing demonstration experience for the construction of smart cities in tourism-oriented cities in the central and western regions.
                        </p><br/>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">                    
                    <el-button type="primary" @click="gx_dialog4 = false">return</el-button>
                </span>
            </el-dialog>
            <el-dialog :visible.sync="gx_dialog5" width="60%">
                <template slot="title">
                    <div class="gx_diatitle">
                        GiuGang
                    </div>
                </template>
                <span>
                    <div class="gxdia_info">
                        <img src="../../assets/images/gx/guigang.png" alt="">
                        <p>
                            With the concept of "golden waterway and ecological livability", the network level will be steadily improved through the optical network city and wireless city,
                             and the comprehensive application project of intelligent port and mixed traffic control mode with certain demonstration function will be built.
                        </p><br/>
                        <p>The pilot projects are mainly established through public information platform, smart urban management, building energy conservation, smart government affairs, 
                            smart medical care and other projects. By 2017, Internet broadband will reach rural households, wireless network will cover the central urban area, and intelligent port,
                             mixed traffic control mode and other comprehensive application projects of informatization with certain demonstration functions will be built, 
                             so as to ensure the status of the core port in the xijiang river basin and promote urban industrial upgrading. By 2020, an ecological system of "smart port"
                              with high information sharing and utilization and efficient cooperation shall be formed.
                        </p><br/>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">                    
                    <el-button type="primary" @click="gx_dialog5 = false">return</el-button>
                </span>
            </el-dialog>
            <el-dialog :visible.sync="gx_dialog6" width="60%">
                <template slot="title">
                    <div class="gx_diatitle">
                        QinZhou————To build a smart industrial city next to the port
                    </div>
                </template>
                <span>
                    <div class="gxdia_info">
                        <img src="../../assets/images/gx/qinzhou.png" alt="">
                        <p>
                            Relying on the regional international shipping and logistics hub of beibu bay and the geographical advantages of commercial and livable bay city, 
                            qinzhou city takes "smart city management, smart people's livelihood and smart industry"
                            The system creates targets for smart qinzhou and implements a number of key projects such as smart ports and smart parks.
                        </p><br/>
                        <p>
                            Qinzhou city has invested 350 million yuan to build digital city, geospatial framework, project life cycle management information system, port information system, 
                            community comprehensive governance information management system and other application systems. Its information technology has been widely used in port scheduling, 
                            urban e-government, digital urban geographic space, community management, urban public security, urban emergency services, urban traffic and other aspects.
                        </p><br/>
                        <p>
                            In the next step, qinzhou city will further promote the integration and intelligent application of urban management, building energy saving, underground pipeline and space,
                             so as to realize the intelligent, modern and low-carbon operation of the city.
                        </p><br/>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">                    
                    <el-button type="primary" @click="gx_dialog6 = false">return</el-button>
                </span>
            </el-dialog>
            <el-dialog :visible.sync="gx_dialog7" width="60%">
                <template slot="title">
                    <div class="gx_diatitle">
                        YuLin————Extensive application of information technology
                    </div>
                </template>
                <span>
                    <div class="gxdia_info">
                        <img src="../../assets/images/gx/yulin.png" alt="">
                        <p>
                            Taking "building a smart city and building a happy yulin" as the goal of building a smart city, yulin city further strengthens digital city management, 
                            community, tourism, transportation, medical care, building energy conservation, and digital management of underground pipelines.
                        </p><br/>
                        <p>
                            At present, yulin information technology is widely used in industry, tourism, transportation, e-government, urban management and other aspects. Among them, digital yulin, 
                            skynet project, digital urban management system and other advanced systems.
                        </p><br/>
                        <p>
                            In the future, yulin will further strengthen digital city management, community, transportation, medical care, building energy conservation, 
                            and digital management of underground pipelines, etc., to promote the urbanization process of yulin by taking the opportunity of creating a smart city.
                        </p><br/>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">                    
                    <el-button type="primary" @click="gx_dialog7 = false">return</el-button>
                </span>
            </el-dialog>
            <el-dialog :visible.sync="gx_dialog8" width="60%">
                <template slot="title">
                    <div class="gx_diatitle">
                        LiuZhou YuFengQu
                    </div>
                </template>
                <span>
                    <div class="gxdia_info">
                        <img src="../../assets/images/gx/yufengqu.png" alt="">
                        <p>
                            We will integrate informatization, industrialization and urbanization to improve the Internet of things and its application,
                             government decision-making and public information services.
                        </p><br/>
                        <p>
                            Combined with the establishment of liuzhou smart city pilot project, various existing information resources in the urban area are planned and integrated in a unified way. 
                            Focusing on the priority of people's livelihood and improving the quality of urban life, the construction of digitization of livable urban environment, 
                            digitization of urban safety prevention and control and digitization of convenient urban life is carried out.
                        </p><br/>
                        <p>
                            It is expected that by 2016, relying on the extensive application of new technologies such as the Internet of things, virtual cluster and tri-network integration, 
                            the "intelligent fish peak" information system with "complete system, in place service, perfect management, in-depth application, security and confidentiality, 
                            and sound foundation" will be initially built.
                        </p><br/>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">                    
                    <el-button type="primary" @click="gx_dialog8 = false">return</el-button>
                </span>
            </el-dialog>
            <el-dialog :visible.sync="gx_dialog9" width="60%">
                <template slot="title">
                    <div class="gx_diatitle">
                        LiuZhou LuZhaiXian————Intelligent industrial county
                    </div>
                </template>
                <span>
                    <div class="gxdia_info">
                        <img src="../../assets/images/gx/luzhaixian.png" alt="">
                        <p>
                            As a satellite city of liuzhou urban and rural integration abatis county, 
                            highlight the "strong county of guangxi industry" and "Chinese ecological structing"
                             characteristics, the integration of existing e-government network management, 
                             community service and the system function based on the construction of wisdom from the county seat, 
                             strive to promote the urbanization and industrialization, urbanization and urban and rural public services, 
                             urbanization and agricultural modernization, such as the coordinated development goal, 
                             to accelerate the development of industry, intelligent and ecological civilization construction.
                        </p><br/>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">                    
                    <el-button type="primary" @click="gx_dialog9 = false">return</el-button>
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