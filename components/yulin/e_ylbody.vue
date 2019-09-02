<template>
        <div>
            <!-- 数字玉林·智慧城市建设 -->
            <div id="e_box_cs" class="bk_cs">
                <el-row class="title_text">
                        Digital Yulin · Intelligent City Construction
                </el-row>
                <el-row style="width: 100vw;height: 80vh;top: 7vh;" >
                    <div id="content" aos="flip-up">
                        <!--特效部分-->
                        <ul class="accordion" id="accordion">
                            <li class="bg1" >
                                <div class="heading">ulin "Wise People's Congress" Platform</div>
                                <div class="bgDescription"></div>
                                <div class="description" >
                                    <h2 style="font-size: 3vh">ulin "Wise People's Congress" Platform</h2>
                                    <p>Yulin's "Wise People's Congress" management platform includes computer terminal (PC) and mobile phone client (APP terminal). It mainly includes five functional systems, including "legislative system", "supervisory system", "representative performance system", "office system"...</p>
                                    <a @click="cs_dialog1 = true"  style="bottom: 0vh;">More &rarr;</a>
                                </div>
                            </li> 
                            <li class="bg2">
                                <div class="heading">Yulin City Inclusive Platform</div>
                                <div class="bgDescription"></div>
                                <div class="description">
                                    <h2 style="font-size: 3vh">Yulin City Inclusive Platform</h2>
                                    <p>Yulin Federation of Trade Unions, Yulin Urban Rural Credit Cooperative and Guangxi Golden Thumb Network Science and Technology Information Co., Ltd. jointly innovated to create a "bank + wisdom city business alliance + trade union members" inclusive service platform. The platform ...</p>
                                    <a @click="cs_dialog2 = true" style="bottom: 0vh;">More &rarr;</a>
                                </div>
                            </li> 
                            <li class="bg3">
                                <div class="heading"> Building Digital Yulin</div>
                                <div class="bgDescription"></div>
                                <div class="description">
                                    <h2 style="font-size: 3vh">Building Digital Yulin</h2>
                                    <p>In the current tide of "deep implementation of big data strategy to speed up the construction of digital Guangxi", China Telecom Yulin Branch has further increased investment and upgraded network capabilities on the basis of existing all-optical networks, vigorously built high-speed ...</p>
                                    <a @click="cs_dialog3 = true">More &rarr;</a>
                                </div>
                            </li>
                            <li class="bg4">
                                <div class="heading">Yulin Research Institute of Big Data</div>
                                <div class="bgDescription"></div>
                                <div class="description">
                                    <h2 style="font-size: 3vh">Yulin Research Institute of Big Data</h2>
                                    <p>Based on Yulin City Big Data Center, Yulin Normal University Big Data Application Innovation Center, Guangxi University Complex System Optimization and Big Data Processing Key Laboratory, Yulin City Big Data Research Institute has been built into an industry big data research ...</p>
                                    <a @click="cs_dialog4 = true"  style="bottom: 0vh;">More &rarr;</a>
                                </div>
                            </li>
                            <li class="bg5">
                                <div class="heading">"Wisdom Yulin" Signed and Started</div>
                                <div class="bgDescription"></div>
                                <div class="description">
                                    <h2 style="font-size: 3vh">"Wisdom Yulin" Signed and Started</h2>
                                    <p>On November 7, 2016, Yulin Smart City Construction Symposium and Signing Ceremony were held in Nanning. Yulin Municipal Government and Shuguang Cloud Computing Co., Ltd. signed a contract on the construction project of Yulin Smart City, which marked the formal start and implementation ...</p>
                                    <a @click="cs_dialog5 = true"  style="bottom: 0vh;">More &rarr;</a>
                                </div>
                            </li>
                            <li class="bg6 bleft">
                                <div class="heading">Choose "National Smart City"</div>
                                <div class="bgDescription"></div>
                                <div class="description">
                                    <h2 style="font-size: 3vh">Choose "National Smart City"</h2>
                                    <p>In April 2015, Yulin City was selected as a pilot city of national wisdom. Building a smart city is an important content and powerful carrier of the "three-year-one activity" in Yulin. On the basis of the previous work, the construction work has entered the top design stage....</p>
                                    <a @click="cs_dialog6 = true" style="bottom: 0vh;">More &rarr;</a>
                                </div>
                            </li>
                        </ul>
                        <!--特效结束-->
                    </div>
                    <!-- 智慧城市建设弹出框内容 -->
                    <el-dialog
                        title="Yulin 'Wise People\'s Congress' Management Platform was officially launched"
                        :visible.sync="cs_dialog1"
                        width="60%"
                        center>
                        <span>
                            <div class="dialog-video1">
                                <video src="@/assets/video/yl_video1.mp4" controls="controls" autoplay="autoplay" width="74%" height="25%"></video>
                            </div>
                            <br>
                            <div class="font-content">
                                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In recent years, based on the new situation and new requirements of the new era, the Standing Committee of the Yulin People's Congress attaches great importance to the informationization construction of the organs of the People's Congress. Taking the management platform of the "wise people's Congress" in Yulin as the entry point, the Standing Committee of the People's Congress of Yulin City has continuously improved the performance level of the People's Congress, and gradually realized the high-efficiency, intelligent supervision.</p>
                                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;It is reported that the management platform of Yulin "Intelligent People's Congress" includes computer terminal (PC) and mobile phone client (APP terminal), mainly including "legislative system", "supervisory system", "representative performance system", "office system", "information system" and other five functional systems, more than 30 subsystems. Through this system, the NPC offices will be more convenient and efficient, and the functions of legislation and supervision can be realized by Internet plus.</p>
                                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The opening and use of the management platform of the Yulin "Wise People's Congress" marks that the Yulin People's Congress has officially entered the era of intelligence. Next step, the Yulin People's Congress will focus on improving the application, function optimization, interconnection and sharing, and strive to build the platform into a new brand and business card for the construction of the Yulin People's Congress.</p>
                            </div>
                        </span>
                    </el-dialog>
                    <el-dialog
                        title="Yulin Wisdom City Trade Union Members'Inclusive Platform Brings on the Jade Expo"
                        :visible.sync="cs_dialog2"
                        width="60%"
                        center>
                        <span>
                            <div class="dialog-img">
                                <img src="@/static/images/city_p2.jpg" alt="" width="70%" height="30%">
                            </div>
                            <br>
                            <div class="font-content">
                                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;On September 15, the reporter saw in the exhibition hall of the 12th Jade Expo that the members of the trade union of Yulin Smart City on the third floor of the China-ASEAN Commodity Exchange Center were enjoying pedestrians at the entrance of the platform hall. The reporter learned that the Yulin Federation of Trade Unions, Yulin Rural Credit Cooperatives and Guangxi Jinthumb Network Science and Technology Information Co., Ltd. has jointly innovated and built an inclusive service platform of "Bank+Intelligent City Business Union+Trade Union Members". The platform will expand trade unions by building a "Guangxi (Yulin) Trade Union Members Service Card" which integrates trade union services, commercial services, financial services, Internet services and other major functions. Members enjoy the scope of service, to achieve the city's preferential labor action "broader service subjects, richer service content, more assurance of service quality, more convenient service mode, full coverage of service objects, multi-win" overall goal.</p>
                                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;According to the on-site staff, the "Guangxi (Yulin) trade union membership service card" is different from the ordinary bank card. It has not only the functions of financial IC card and the special service of the contractor, but also the functions of membership management and related services, so as to realize the effect of multi-purpose and multi-industry application of one card. At present, card holders can enjoy free or inclusive services provided by the service institutions affiliated to trade union organizations. Trade union assistance funds such as life assistance, medical assistance, golden autumn assistance and so on can be issued through the "Guangxi (Yulin) trade union member service card"; they can enjoy various conveniences and preferential services of the corresponding public service "one-card" in the area. It also enjoys all kinds of affordable services of bank members. In addition, cardholders can easily get preferential and welfare information from local contractors, and they will get corresponding discounts when they consume designated goods and services.</p>
                            </div>
                        </span>
                    </el-dialog>
                    <el-dialog
                        title="Intelligent City Construction Helps the Development of Digital Guangxi"
                        :visible.sync="cs_dialog3"
                        width="60%"
                        center>
                        <span>
                            <div class="dialog-img">
                                <img src="@/static/images/city_p3.png" alt="" width="70%" height="30%" >
                            </div>
                            <br>
                            <div class="font-content">
                                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;China Telecom actively promotes the construction of smart cities, providing comprehensive, convenient and personalized services to users in three areas: smart government, smart industry and smart people's livelihood, and further promoting the development of urbanization, informatization and industrialization.</p>
                                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As the "national team" and "main force" of informationization construction, China Telecom Yulin Branch took the lead in building a smart city experience hall in Yulin City in September 2015, becoming the first comprehensive interactive experience science popularization hall shop in Yulin City named after a smart city and displaying the theme of smart city construction. It has set up three sections of intelligent city image display area and smart government, smart industry and smart people's livelihood experience area. By means of multimedia, exhibition board, physical display and manual explanation, it combines the practical application scenarios of various industries, groups, work and life, and builds the experience environment of smart application, so as to let the people who come to experience it. We personally feel that cloud computing, Internet of things, big data, Internet +, AI and other new generation of information technology bring us high efficiency and convenience, so that "smart city" can be seen and touches, thus promoting the application level of information technology in Yulin.</p>
                            </div>
                        </span>
                    </el-dialog>
                    <el-dialog
                        title="Yulin Research Institute of Big Data"
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
                                <span style="font-size: 2vh;font-weight:550;">Four research areas:</span><br>
                                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Around the People's Government of Guangxi Zhuang Autonomous Region, the Action Plan for Promoting the Development of Big Data (Guizhengfa [2016], No. 59) was issued, and the direction of scientific research was refined according to the needs of local government and industry development. The research fields were mainly focused on the big data of education, agriculture, tourism and overseas Chinese affairs, and health and medical services.</p>
                                <span style="font-size: 2vh;font-weight:550;">Construction objectives:</span><br>
                                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Based on Yulin City Big Data Center, Yulin Normal University Big Data Application Innovation Center, Guangxi University Complex System Optimization and Big Data Processing Key Laboratory, Yulin City Big Data Research Institute has been built into an industry big data research institute facing the whole city and even the whole region, which can provide references for the development of big data industry in the whole city and the whole region. Provide technical support and services, form a virtuous circle of using scientific research capabilities to provide industry services, using industry services to achieve talent training, and using talent training to support scientific research capacity building.</p>
                            </div>
                        </span>
                    </el-dialog>
                    <el-dialog
                        title="Yulin Smart City Construction Signing Ceremony Held in Nanning"
                        :visible.sync="cs_dialog5"
                        width="60%"
                        center>
                        <span>
                            <div class="dialog-img">
                                <img src="@/static/images/city_p5.png"  width="70%" height="30%" >
                            </div>
                            <br>
                            <div class="font-content">
                                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;On November 7, the Symposium and signing ceremony of Yulin Smart City Construction was held in Nanning. Yulin Municipal Government and Shuguang Cloud Computing Co., Ltd. signed a contract on the construction project of Yulin Smart City, marking the formal start and implementation of the "Smart Yulin" project. Mayor Su Haitang, Vice Mayor Li Zhenpin, Director and Senior Vice President of Shuguang Information Industry Co., Ltd. and President Nie Hua of Shuguang Cloud Computing Co., Ltd. attended the signing ceremony.</p>
                                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Su Haitang thanked Nie Hua and his delegation for their arrival and reported to them the economic and social development of Yulin, especially the construction of urban informatization. He said that "smart city" is an advanced stage of urban informatization development, an intelligent response to urban management, public services, livelihood security, business activities and other urban needs. It is of great significance to improve government management and improve the quality of life of residents. In recent years, our city attaches great importance to the construction of urban informatization, and has made remarkable achievements in e-government and information network construction, which lays a good foundation for the construction of "smart city" in Yulin City. The contracted "Smart City" construction project in Yulin City includes 19 projects such as Intelligent Government Platform, Intelligent Community, Intelligent Park and Intelligent Pharmaceutical Capital. We will promote the project according to the principle of "overall planning and step-by-step implementation". After the completion of the project, we will surely make intellectualized management of the city, scientific decision-making of the government and characteristic production. Industry development plays a great role in promoting. In the future construction, we sincerely hope that Guangxi Zhongke Shuguang Cloud Computing Co., Ltd. (Zhongke Shuguang) will give full play to its technological and resource advantages, devote all efforts to the project construction, and ensure that the "Smart City" construction project of Yulin City will become a model project of "Smart City" construction.</p>
                                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;After hearing the report, Nie Hua expressed his pleasure at the achievements made in the economic and social development of Yulin, and was honored to be able to participate in the construction of "wisdom city" in Yulin. In the future, Sino-Tech Dawning will devote the best technology and the greatest strength to the project construction, and work with the Yulin Municipal Government to compose a new chapter of "Wisdom Yulin" that "Make Yulin more wise and make life happier".</p>
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
                                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In April 2015, our city was selected as the pilot of National Smart city. Creating a smart city is an important content and powerful carrier of the "three-year-one activity" in Yulin City. Based on the previous work, the creation work has entered the top design stage. Sixteen projects will be implemented steadily, and it will take three to five years to build a national smart city.</p>
                                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Our city's goal of creating a national wisdom city is mainly to promote the construction of new urbanization in Yulin wisely by creating a wisdom city, improve the scientific nature of urban planning and construction, improve the efficiency and refinement of urban management, improve public services, improve people's livelihood, promote industrial transformation and upgrading, and promote economic and social development in an all-round way. Intelligent urban management, happy people's livelihood, industrial transformation and upgrading framework; information technology fully supports the rapid and sustainable development of Yulin's economy and society, comprehensive visualization of urban operation status, comprehensive prevention and control of urban safety, effective support for urban operation management decision-making; people's livelihood has been further improved, and social public services have been provided. To achieve equitable and convenient development, the people's sense of well-being doubled, and build a service-oriented government; to achieve sound economic transformation and upgrading, and basically build a wise Beibu Gulf central city.</p>
                            </div>
                        </span>
                    </el-dialog>
                </el-row> 
            </div>
            
            <!-- 数字玉林·“互联网+”政务服务板块 -->
            <div id="e_box_zw" class="bk_zw">
                <el-row class="title_text">Digital Yulin · " Internet + " government services</el-row>
                <el-row class="zhengwu_module1" style="overflow-y:auto; " aos="fade-up">
                    <template v-if="zw_click == 0">
                        <div class="zw_content">
                            <p class="zw_ctTitle">Insert the wings of "science and technology" to light up the new business card of Yulin Intelligence Court</p>
                            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Since this year, Yulin Intermediate People's Court has taken the problem-oriented, application-oriented and innovation-oriented measures to accurately grasp the new progress and application of information technology, such as cloud computing and big data. It has vigorously promoted the construction of "smart court", launched a number of new initiatives of the Yulin model, and created the Yulin model of the smart court.</p>
                            <p style="font-weight:550;">Full Business Online Processing: Creating a New Network Court</p>
                            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;From January to November 2018, the city's courts accepted 37,522 cases of various types, up 6.56% year on year. Among them, 28111 cases were accepted, up 4.02% year on year, 9411 cases were accepted and executed, up 14.94% year on year, 3583 criminal cases were accepted, up 0.14% year on year, 23,338 civil and commercial cases were accepted, up 2.23% year on year, and the statutory trial limit was for internal trial. The knot rate was 100%. The above data are from the online real-time statistics of the "Intelligent Court" system of Yulin Intermediate People's Court.</p>
                            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In the two-level courts of Yulin City, all cases are put on file from filing to filing, two-dimensional code filing, random case division, intelligent writing of documents, one-key filing, open case flow and other systems are applied comprehensively, which integrates the application of information sites such as science and technology courts, remote access, command center, remote interrogation and so on in all stages of case trial. We can see the progress, realize the dynamic monitoring of judicial execution activities, strengthen the supervision and restriction of every link in the operation of judicial power and execution power, and standardize judicial acts.</p>
                            <p style="font-weight:550;">Opening the whole process in accordance with the law-building Sunshine Court</p>
                            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"Disclosure of case procedure", "live broadcast of court hearing", "Internet access of judgment documents", "Disclosure of execution information"... These information systems have opened up the channels for the information disclosure of court cases, enabled the judiciary to operate in the sunshine, accept the supervision of the masses and the media, and further enhance the credibility of the judiciary. The courts of the whole city are pushing for the publication of judgment documents and live broadcasting of court hearings on the Internet, and constantly expanding the scope of publicity of judgment documents and the number of live cases. As of November 29 this year, 64 science and technology courts have been set up in the whole city, recording more than 65,000 court trials per time, 66,723 judgment documents are online, 100% of them are online, and 7,132 live court trials are broadcast.</p>
                            <p style="font-weight:550;">All-round Intelligent Service-Building Intelligent Court</p>
                            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Let the data run more, let the masses run less "- this is an important goal of the city's courts to build intelligent courts. Since the implementation of the registration system in the national courts in 2015, the threshold for mass lawsuits has been lowered, and litigation cases have increased substantially. The courts of the whole city have actively introduced scientific and technological means to improve their ability to serve the masses in litigation, so that the parties can participate in litigation expediently and quickly.</p>
                            <br>
                            <br>
                        </div>
                    </template>
                    <template v-if="zw_click == 1">
                        <div class="zw_content">
                            <p  class="zw_ctTitle">Building Digital Yulin and Serving the Strategy of Dongrong</p>
                            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Recently, our city (Yulin City) held the work conference on big data development and government service in 2019. This conference is the first one after the organization reform, the development of big data and the integration of government service. It has the functions of speeding up the development of big data, deepening the reform of "detention uniform" and improving the quality of government service in an all-round way. Significance. Qiu Dekui, Standing Committee and Executive Vice Mayor of the Municipal Committee, attended the meeting.</p>
                            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Qiu Dekui stressed that the development of big data has risen to the national strategy. We should implement the national strategy of big data development in an all-round way, plan for a high starting point, promote high-quality development, vigorously build digital Yulin, and adhere to the "six strengthens": strengthen responsibility, create a new situation of big data development and government services; and strengthen facilities construction. Strengthen the foundation of digital development; Strengthen industrial convergence to promote the vigorous development of digital economy; Strengthen the "100-day hard work" activities to serve the implementation of the "Eastern Finance" strategy; Strengthen the "simple operation" of government services, and constantly enhance the ability to serve the people; Strengthen e-government, promote the enhancement of government credibility, and strive to open an innovative era for the whole city. The development of big data and the new situation of government service.</p>
                            <br>
                            <br>
                        </div>
                    </template>
                    <template v-if="zw_click == 2">
                        <div class="zw_content">
                            <p class="zw_ctTitle">Yulin City Holds the Work Conference on Big Data Development and Government Services to Sound the Trumpet of Big Data Development</p>
                            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;On April 26, the work conference on big data development and government service in 2019 was held in the Municipal Culture and Art Center, which officially sounded the bugle of big data development. This is the first meeting after the integration of big data development and government service in the whole city. It is a milestone for speeding up the development of big data in our city, deepening the reform of "releasing control clothing" and improving the quality of government service in an all-round way.</p>
                            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;At the meeting, Jiang Xiangsong, Director-General of the Municipal Bureau of Big Data Development and Government Services, made a report on promoting Big Data Development and Government Services. Qiu Dekui, Standing Committee of the Municipal Committee and Executive Vice Mayor of the CPC Municipal Committee, affirmed the achievements made in the last year's government service work and adherence to the digital strategy driving strategy, the combination of research and production, and the full promotion of frontier information, e-commerce and other industries. Qiu Dekui stressed that the development of big data has risen to the national strategy. We should implement the national strategy of big data development in an all-round way, plan for a high starting point, promote high-quality development, vigorously build digital Yulin, and adhere to the "six strengthens": strengthen responsibility, create a new situation of big data development and government services; and strengthen facilities construction. Strengthen the foundation of digital development; Strengthen industrial convergence to promote the vigorous development of digital economy; Strengthen the "100-day hard work" activities to serve the implementation of the "Eastern Finance" strategy; Strengthen the "simple operation" of government services, and constantly enhance the ability to serve the people; Strengthen e-government, promote the enhancement of government credibility, and strive to open an innovative era for the whole city. The development of big data and the new situation of government service provide solid guarantee for our city to fight well the "three major wars" and realize the "six major breakthroughs".</p>
                            <br>
                            <br>
                        </div>
                    </template>
                    <template v-if="zw_click == 3">
                        <div class="zw_content">
                            <p class="zw_ctTitle">Yulin City Big Data Development and Government Service Bureau: From "Can Do" to "Easy Do"</p>
                            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Yulin News Network - Yulin Daily News (Reporter Zhang Guanzhong) Journalist recently learned from Yulin City Big Data Development and Government Service Bureau that, since this year, Yulin City has accelerated the construction of digital government affairs. Government services have changed from entity hall to online and offline integration, from "capable" to "simple" to reduce links, time limits, materials, costs and running errands. "One reduction" will further enhance the ability and level of the government to serve enterprises and the masses.</p>
                            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Among them, in terms of time reduction, from series approval to parallel approval. Yulin actively reformed the examination and approval mode, and changed from serial examination and approval linking up successively to parallel examination and approval advancing synchronously. Reengineering and sorting out the whole process of investment project approval service, the total time limit for project approval is reduced by 82%, the whole process of real estate registration is re-engineered, and the time limit for completion is shortened by about 60% compared with the original process; the start-up process of reengineering enterprise is synchronized with the push of enterprise information, and the start-up time of enterprise is reduced from 15 days to 1 day.</p>
                            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In terms of material reduction, from "running many times" to "running once". Starting with declaration materials, we should strengthen data sharing, cancel duplicate submissions, simplify materials into forms, compile material lists, and promote "running at most once". Municipal level took the lead in publishing 1191 items of "three lists" and "running at most once" in all departments in the district, accounting for 99.34%, 91.93% at County (city, district) level and 98.97% at Township level.</p>
                            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In terms of leg reduction, from offline to digital government. Implementing the big data development strategy and promoting online services, there are 1074 online consultation applications at the municipal level, accounting for 92.11% of the total transactions, ranking in the forefront of the region. For example, a new generation of intelligent provident fund information platform has been set up in our city, which implements a new service mode of "invisible examination and approval" for such businesses as opening accounts, depositing online, withdrawing retirement and withdrawing from work. It is the first time in the region to realize self-accounting of housing provident fund loans, synchronous switching of credit reporting and seamless connection. We will comprehensively promote the pilot reform of self-declaration of enterprise names, implement electronic business licenses and full-process electronic registration management, and realize that all kinds of enterprises, individual businesses and farmers'professional cooperatives can obtain electronic business licenses online directly, so that they do not have to go out to "do online licences".</p>
                            <br>
                            <br>
                        </div>
                    </template>
                </el-row>
                <el-row class="zhengwu_module2" aos="flip-right">
                    <el-col class="zhengwu_module2_1">
                        <div class="bs-example" style="background-color: transparent;border: 0;" >
                            <div class="row"  style="top: 2vh;">
                                <div class="col-sm-6">
                                    <div class="ih-item square effect3 bottom_to_top"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
                                        <div @click="zw_click = 0">
                                        <a>
                                            <div class="img">
                                                <img src="@/assets/images/yulin/zw_p2.jpg" alt="img" style="background-size: 100% 100%;">
                                            </div>
                                            <div class="info">
                                                <p style="font-size: 1.5vh;color:cyan;border-bottom:1px solid rgb(255, 255, 255);">Insert the wings of "science and technology" to light up the new business card of Yulin Intelligence Court</p>
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
                            <div class="row"  style="top: 2vh;">
                                <div class="col-sm-6">
                                    <div class="ih-item square effect3 bottom_to_top"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
                                        <div @click="zw_click = 1">
                                        <a >
                                            <div class="img">
                                                <img src="@/assets/images/yulin/zw_p3.jpg" alt="img" style="background-size: 100% 100%;">
                                            </div>
                                            <div class="info">
                                                <p style="font-size: 1.5vh;color:cyan;border-bottom:1px solid rgb(255, 255, 255);">Building Digital Yulin and Serving the Strategy of Dongrong</p>
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
                                <div class="row"  style="top: 2vh;">
                                    <div class="col-sm-6">
                                        <div class="ih-item square effect3 bottom_to_top"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
                                            <div @click="zw_click = 2">
                                            <a >
                                                <div class="img">
                                                    <img src="@/assets/images/yulin/zw_p1.jpg" alt="img" style="background-size: 100% 100%;">
                                                </div>
                                                <div class="info">
                                                    <p style="font-size: 1.5vh;color:cyan;border-bottom:1px solid rgb(255, 255, 255);">The conference of big data government service sounds the trumpet of big data development</p>
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
                            <div class="row">
                                <div class="col-sm-6">
                                    <div class="ih-item square effect3 bottom_to_top"  style="bottom: 5vh;border: 0.5vw;background-size: 100% 100%;">
                                        <div @click="zw_click = 3">
                                            <a >
                                                <div class="img">
                                                    <img src="@/assets/images/yulin/zw_p4.jpg" alt="img" style="background-size: 100% 100%;">
                                                </div>
                                                <div class="info">
                                                    <p style="font-size: 1.5vh;color:cyan;border-bottom:1px solid rgb(255, 255, 255);">Yulin City Big Data Development and Government Service Bureau: From "Can Do" to "Easy Do"</p>
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
            <!-- 数字玉林·智慧旅游建设板块 -->
                <div id="e_box_ly" class="bk_ly">
                        <el-row class="title_text">
                                Digital Yulin · Intelligent Tourism Construction
                        </el-row>
                        <el-row class="travel_module1">
                            <div id="main">
                                <ul>
                                    <li style="top: 12vh;" aos="fade-up" aos-anchor-placement="bottom-bottom"> 
                                        <img src="@/assets/images/yulin/travel_p1.png" alt="" style="width: 15vw;height:50vh" >
                                           <div class="info">
                                               <h1 style="font-size: 2vh;">Construction of Intelligent Tourism in Yulin City</h1>
                                              <p>———History of tourism culture is rich </p>
                                              <a href="/e_yl_ctly1" target="_blank">details</a>
                                       </div>
                                    </li>
                                    <li aos="fade-up" aos-anchor-placement="bottom-bottom"> 
                                        <img src="@/assets/images/yulin/travel_p2.png" alt=""  style="width: 15vw;height:50vh">
                                       <div class="info">
                                        <h1 style="font-size: 2vh;">Construction of Intelligent Tourism in Yulin City</h1>
                                          <p>———Objective demand of tourism market</p>
                                          <a href="/e_yl_ctly2" target="_blank" >details</a>
                                       </div>
                                    </li>
                                    <li aos="fade-up" aos-anchor-placement="bottom-bottom"> 
                                        <img src="@/assets/images/yulin/travel_p3.png" alt="" style="width: 15vw;height:50vh" >
                                       <div class="info">
                                        <h1 style="font-size: 2vh;">Construction of Intelligent Tourism in Yulin City</h1>
                                          <p>———Three-year Action Plan for the Development of Wisdom Tourism in Yulin</p>
                                          <a href="/e_yl_ctly3" target="_blank" >details</a>
                                       </div>
                                    </li>
                                    <li style="top: 12vh;" aos="fade-up" aos-anchor-placement="bottom-bottom"> 
                                        <img src="@/assets/images/yulin/travel_p4.png" alt=""  style="width: 15vw;height:50vh" >
                                        <div class="info" style="height: 26vh;">
                                            <h1 style="font-size: 2vh;">Construction of Intelligent Tourism in Yulin City</h1>
                                           <p>———Construction of Zhizhirong County (a famous tourism county with national characteristics)</p>
                                           <a href="/e_yl_ctly4" target="_blank" >details</a>
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
                                        <h1 style="font-size: 2vh;">Construction of Intelligent Tourism in Yulin City</h1>
                                          <p>———Construction of Intelligent Tourism in Rongxian County</p>
                                          <a href="/e_yl_ctly5" target="_blank" >details</a>
                                       </div>
                                    </li>
                                    <li aos="fade-up" aos-anchor-placement="bottom-bottom"> 
                                        <img src="@/assets/images/yulin/travel_p6.png" alt="" style="width: 15vw;height:50vh" >
                                       <div class="info">
                                        <h1 style="font-size: 2vh;">Construction of Intelligent Tourism in Yulin City</h1>
                                          <p>———Municipal School and School Promote Project Together</p>
                                          <a href="/e_yl_ctly6" target="_blank">details</a>
                                       </div>
                                    </li>
                                    <li aos="fade-up" aos-anchor-placement="bottom-bottom"> 
                                        <img src="@/assets/images/yulin/travel_p7.png" alt=""  style="width: 15vw;height:50vh" >
                                       <div class="info">
                                        <h1 style="font-size: 2vh;">Construction of Intelligent Tourism in Yulin City</h1>
                                          <p>———Put forward the plan of "Yulin Global Tourism Big Data Platform"</p>
                                          <a href="/e_yl_ctly7" target="_blank" >details</a>
                                       </div>
                                    </li>
                                    <li style="top: 12vh;" aos="fade-up" aos-anchor-placement="bottom-bottom"> 
                                        <img src="@/assets/images/yulin/travel_p8.png" alt="" style="width: 15vw;height:50vh" >
                                        <div class="info">
                                            <h1 style="font-size: 2vh;">Construction of Intelligent Tourism in Yulin City</h1>
                                           <p>———Progress of Project Construction</p>
                                           <a href="/e_yl_ctly8" target="_blank" >details</a>
                                        </div>
                                     </li>
                                </ul>
                             </div>
                        </el-row>
                    </div>
                    <!-- 数字玉林·大数据助力精准扶贫 -->
            <div id="e_box_fp" class="bk_fp">
                <el-row class="title_text">
                        Digital Yulin · Big Data Helps Accurate Poverty Alleviation
                </el-row>
                <el-row >
                    <div id="wrap" aos="flip-left">
                    <ul >
                        <li>
                        <a href="" class="a1">
                            <img src="@/assets/images/yulin/fp_p1.png">
                            <div class ="divA">
                                <p class="p1" style="line-height:2.5vh;font-size: 1.6vh;font-weight: 550;">Upgrading of Big Data Supervisory Platform of Bobai People's Livelihood Fund in Yulin City</p>
                                <p class="p2">After five months of trial operation, the Bobai County People's Livelihood Funds Big Data Supervisory Platform has been...</p>
                            </div>
                        </a>
                        <a class = "a2"  href="/e_yl_ctfp1" target="_blank">
                                <p class="p4" style="line-height: 3vh;top: 0.3vh;">Upgrading of Big Data Supervisory Platform of Bobai People's Livelihood Fund in Yulin City</p>
                                <p class="p5">After five months trial operation, the Bobai <br>County People's Livelihood Funds Big Data Supervisory Platform has been ..</p>
                                <p class="p7">See details</p>
                        </a>
                    </li>
                    <li>
                        <a href="" class="a1">
                            <img src="@/assets/images/yulin/fp_p2.jpg">
                            <div class ="divA">
                                <p class="p1" style="line-height:2.5vh;font-size: 1.6vh;font-weight: 550;">Yulin City Big Data Accurately Helps Poor Students to Go to School</p>
                                <p class="p2">In order to realize the precise education subsidy and ensure that the students from poor households who set up archives and licensing ..</p>
                            </div>
                        </a>
                        <a class = "a2" href="/e_yl_ctfp2" target="_blank">
                                <p class="p4" style="line-height: 3vh;top: 0.3vh;">Yulin City Big Data Accurately Helps Poor Students to Go to School</p>
                                <p class="p5">In order to realize the precise education subsidy<br> andensure that the students from poor households who set up archives and licensing ...</p>
                                <p class="p7">See details</p>
                        </a>
                    </li>
                    <li>
                        <a href="" class="a1">
                            <img src="@/assets/images/yulin/fp_p3.jpg">
                            <div class ="divA">
                                <p class="p1" style="line-height:2.5vh;font-size: 1.6vh;font-weight: 550;">Bobai County of Yulin City uses "big data" to focus on people's livelihood funds</p>
                                <p class="p2">Establishing a large data platform for data comparison is the foundation of Bobai County's pioneering electronic dynamic supervision ...</p>
                            </div>
                        </a>
                        <a href="" class = "a2" href="/e_yl_ctfp3" target="_blank">
                                <p class="p4" style="line-height: 3vh;top: 0.3vh;">Bobai County of Yulin City uses "big data" to focus on people's livelihood funds</p>
                                <p class="p5">Establishing a large data platform for data <br>comparison is the foundation of Bobai County's pioneering electronic dynamic supervision...</p>
                                <p class="p7">See details</p>
                        </a>
                    </li>
                    <li>
                        <a href="" class="a1">
                            <img src="@/assets/images/yulin/fp_p4.jpg"/>
                            <div class ="divA">
                                <p class="p1" style="line-height:2.5vh;font-size: 1.6vh;font-weight: 550;">"Poverty Alleviation Cloud" Big Data in Xingye County of Yulin City Helps Poverty Alleviation</p>
                                <p class="p2">Xingye County develops and establishes a large data platform of "poverty alleviation cloud" in Xingye County around special actions such as...</p>
                            </div>
                        </a>
                        <a href="" class = "a2" href="/e_yl_ctfp4" target="_blank">
                                <p class="p4" style="line-height: 3vh;top: 0.3vh;">"Poverty Alleviation Cloud" Big Data in Xingye County of Yulin City Helps Poverty Alleviation</p>
                                <p class="p5">Xingye County develops and establishes a large <br>dataplatform of "poverty alleviation cloud" in Xingye County around special actions such as ...</p>
                                <p class="p7">See details</p>
                        </a>
                    </li>
                    <li>
                        <a href="" class="a1">
                            <img src="@/assets/images/yulin/fp_p5.jpg"/>
                            <div class ="divA">
                                <p class="p1" style="line-height:2.5vh;font-size: 1.6vh;font-weight: 550;">"Hard Way" of Poverty Alleviation by E-commerce in Luchuan Michang Town of Yulin City</p>
                                <p class="p2">Michang Town pays attention to the promotion of e-commerce poverty alleviation model, implements accurate poverty alleviation of rural e-commerce...</p>
                            </div>
                        </a>
                        <a href="" class = "a2" href="/e_yl_ctfp5" target="_blank">
                                <p class="p4" style="line-height: 3vh;top: 0.3vh;">"Hard Way" of Poverty Alleviation by E-commerce in Luchuan Michang Town of Yulin City</p>
                                <p class="p5">Michang Town pays attention to the promotion of <br>e-commerce poverty alleviation model, implements accurate poverty alleviation of rural e-commerce...</p>
                                <p class="p7">See details</p>
                        </a>
                    </li>
                    <li>
                        <a href="" class="a1">
                            <img src="@/assets/images/yulin/fp_p6.jpg">
                            <div class ="divA">
                                <p class="p1" style="line-height:2.5vh;font-size: 1.6vh;font-weight: 550;">Pre-supervision of livelihood funds in Bobai County, Yulin City</p>
                                <p class="p2">Since this year, in order to break through the blind area of prior supervision, the Discipline Commission of Bobai County has comprehensively upgraded...</p>
                            </div>
                        </a>
                        <a href="" class = "a2" href="/e_yl_ctfp6" target="_blank">
                                <p class="p4" style="line-height: 3vh;top: 0.3vh;">Pre-supervision of livelihood funds in Bobai County, Yulin City</p>
                                <p class="p5">Since this year, in order to break through the <br>blind areaof prior supervision, the Discipline Commission of Bobai County has comprehensively upgraded and...</p>
                                <p class="p7">See details</p>
                        </a>
                    </li>
                </ul>
            </div>
        </el-row>
    </div>
    <!-- 数字玉林·扶持地方特色产业 -->
            <div id="e_box_cy" class="bk_cy">
                <el-row class="title_text">
                        Digital Yulin · Supporting Local Characteristic Industries
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
                                    <p style="color: #000;text-align: center;font-size: 3vh;font-weight: 550;margin-top: 2vh;line-height: 4vh;">Yulin: Big Data Opens a New Age of Intelligent Agriculture</p>
                                    <p style="margin-top: 2vh;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Big data ushered in a new era of smart agriculture. Yulin City has built five county-level operation centers and 1078 standard stations. Information enters villages and enters households on the "highway". People can see the real-time appearance of each golden orange with their fingers, as well as the temperature, humidity and carbon dioxide concentration on the spot; just need to sweep the two-dimensional code on the packaging, we can accurately understand the information of the whole process of agricultural products from production, processing, circulation, storage to sales... This is the "smart agriculture" experienced in the Intelligent Agriculture Experience Hall of Xingye Fengming Yajiang Eco-breeding (Core) Demonstration Zone.</p>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In recent years, our city has made great efforts to promote the deep integration of "Internet + agriculture" modern information technology and agricultural production, operation, management, service and all aspects of rural economic and social fields, vigorously develop intelligent agriculture, and speed up the development of agricultural modernization, so as to inject strong vitality into the implementation of Rural Revitalization Strategy.</p>
                                    <br>
                                    <p style="color: #000;font-size: 2vh;font-weight: 550;">Building Data Management Platform and Developing Intelligent Agriculture</p>
                                    <br>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"The use of agricultural remote sensing technology, satellite imagery, UAV, GPS and other equipment to provide planning services for Luchuan Lufeng Orange Traditional Chinese Medicine Industry (core) demonstration area; for Luchuan County Hot Spring Town, Ma Po Town, Liangtian Town, more than 10,000 acres of land circulation to provide aerial photography services. Complete the investigation and confirmation of large-scale industrial projects such as Chinese herbal medicine base, characteristic agricultural base and potato base in Yuzhou District. Using low-altitude image and remote sensing technology to create a "map" of the distribution of agricultural and forestry resources is only one example of the development of smart agriculture in our city.</p>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;At present, our city has made a deep integration plan of internet, big data, artificial intelligence, agriculture and service industry in the "Work Program of Yulin City's Deeply Implementing Big Data Strategy and Accelerating the Construction of Digital Yulin". We will build a data management platform for agriculture and rural areas and develop smart agriculture. Using Internet of Things, low-altitude image, remote sensing and other technologies to create a "map" of the distribution of agricultural and forestry resources, strengthen the support of data base, and improve the level of intelligent management such as agricultural situation assessment, disaster warning, price monitoring, yield prediction, land right confirmation.</p>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Relying on the modern characteristic agricultural demonstration area, we will develop the application of intelligent technology of characteristic superior industries, focusing on the digital construction of the bases of optimum selection of rice, medicinal materials, livestock breeding, Shatianyou in 11 autonomous region-level modern characteristic agricultural demonstration areas of Yulin City, and accelerate the construction of the traceability management platform of agricultural product quality and safety information. We will promote the integrated application of intelligent and automated equipment technology, promote the intelligent transformation of agricultural machinery and production facilities, and realize intelligent operations such as water-saving irrigation, soil testing and fertilization, positioning farming of agricultural machinery, accurate feeding, automatic disease diagnosis, etc. By 2020, our city will take the lead in realizing the full coverage of Internet of Things technology application in the modern agricultural industrial park at the autonomous region level.</p>
                                    <br>
                                    <p style="color: #000;font-size: 2vh;font-weight: 550;">Information Entering Village and Household Promoting Agricultural Industry Upgrading</p>
                                    <br>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In the circulation of agricultural products, the Municipal Agricultural and Rural Bureau has actively constructed the upward system of agricultural products, created new growth points for farmers'continuous income increase, and successively carried out the construction of information into villages and households in counties (cities and districts).</p>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;At present, five project counties in Yulin City have been built according to the "six possessions" standard of "one village, three stations" with places, personnel, equipment, broadband, web pages and sustainable operation capability. They have also built a good information service system of operation center and beneficial agricultural information cooperative, so as to realize that ordinary peasant households do not go to villages and new agricultural operators do not go out of their homes. Enjoy convenient information services and agricultural products upstream services. Each administrative village constructs one standard station, one professional station and one simple station. It establishes the information service framework of cities, counties and villages in Yulin City. It connects with the autonomous region, and jointly builds the information service framework of "four levels" linkage, and opens up the rural information channel. At the same time, we will open an online comprehensive information service platform and integrate diversified service resources, such as agricultural-related government information platform, so that the Agricultural Information Society will become an important platform for serving "agriculture, countryside and farmers".</p>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Up to now, five county-level operation centers (Bobai, Luchuan, Xingye, Rongxian, Beiliu), 1078 standard stations, 1078 professional stations and 1078 simple stations have been built in seven project counties of the whole city. A total of 1735 village-level informants have been trained, and the work of information entering villages and households ranks first in Guangxi. (Reporter Zhou Lihua, correspondent He Wanli)</p>
                                    <br>
                                    <br>
                                </span>
                                <span data-for="gridly">
                                    <p style="color: #000;text-align: center;font-size: 3vh;font-weight: 550;margin-top: 2vh;line-height: 4vh;">Rely on "Internet +", Yulin Chinese medicine port to build "big data"</p>
                                    <p style="margin-top: 2vh;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;After the establishment of the database, like the library searcher, when purchasing medicinal materials, it is not necessary to go through half of the market as before to find medicinal materials. Only by inputting the desired medicinal materials into the searcher, it is easy to search the stores with the required varieties for sale. Buyers and sellers can easily search for matches, find business opportunities and facilitate intercourse Yi.</p>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Supply Name: Paeonia lactiflora, Specification: Sulphur-free, Origin: Anhui, Quantity: Bulk, Unit Price: Negotiation"... In recent days, members of the Yulin Chamber of Commerce and Industry of Traditional Chinese Medicines are coming out early and returning late every day. They are doing a "big thing" with books and pens: visiting one by one the merchants who operate Chinese medicines in the market, conducting a "big census" of the varieties of medicines sold in each store, and these data will be offspring. Detailed records, waiting for the completion of the "census" work, these data will be entered into the computer, and eventually form the Yulin Chinese medicine market database. The establishment of this database may bring a greater development opportunity to the market of traditional Chinese medicine in Yulin City.</p>
                                    <br>
                                    <p style="color: #000;font-size: 2vh;font-weight: 550;">Changing the Traditional Sales Model</p>
                                    <br>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Throughout the development of Yulin traditional Chinese medicine market, Yulin traditional Chinese medicine market has been established for 26 years. The trade of traditional Chinese medicines in Yulin was established and put into use in 1988 from the market of traditional Chinese medicines in the vicinity of the railway station in the 1980s, then to the modern comprehensive market of traditional Chinese medicines in Yinfeng International Port of Yulin nowadays. The pace is from the polder to the city, from the stall to the shops, and the turnover is increasing year by year. Nowadays, Yulin Chinese medicine market has become the largest distribution and wholesale market of Chinese medicine in South and Central South China. Chinese medicine is exported to home and abroad, and foreign businessmen who come to Yulin every year to trade Chinese medicine are not counted. Number.</p>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The market is changing, the transaction is changing, but the way of operation has not changed. Most of the pharmacists in the market of traditional Chinese medicines are still in accordance with the inherent "stall" mode, waiting for customers to come to the door, while foreign merchants to choose medicines, but also in the market to find the desired varieties in half a day, if there are more varieties to buy, it will take a lot of time.</p>
                                    <br>
                                    <p style="color: #000;font-size: 2vh;font-weight: 550;">With the help of "Internet +"</p>
                                    <br>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The shortcomings of the traditional sales model, to a certain extent, plague operators and purchasing pharmaceuticals merchants, which has become a barrier across the road of the growth of the Chamber of Commerce. Faced with this trouble, members of the chamber of Commerce held several meetings to discuss why they did not focus on the direction of "Internet +" proposed by the state.</p>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;With the help of Internet information technology and through collecting and constructing database, the preliminary function of this database is to set up a similar library searcher. When pharmacists come to the port of traditional Chinese medicine to select medicinal materials, they do not need to go through half of the market to find medicinal materials as before. They just need to input the medicinal materials they want to find on the searcher, so they can be very relaxed. Search for stores that need to sell and go straight to the theme. Through such standardized supply and demand information, we can break the traditional decentralized "floor stall" business model of traditional Chinese medicines. Buyers and sellers can easily search for matches, find business opportunities and facilitate transactions.</p>
                                    <br>
                                    <p style="color: #000;font-size: 2vh;font-weight: 550;">Bold water test to speed up the "big data era"</p>
                                    <br>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; The leadership of the Chamber of Commerce eventually took the lead, but after all, they chose to cooperate with a website. After preliminary preparations, these days they began to collect data thoroughly for the drug dealers in the Chinese medicine market, and conduct a "general survey" of the varieties of medicinal materials sold in each store.</p>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;"Collecting preliminary data, establishing a database and providing quick index function for commodity selection are only the first steps we envisage." According to Wu Zhiying, Secretary of the Party branch of the Chinese herbal medicine market in Yulin, now, from the national level to the common people, they are advocating "Internet +"Road, this Chamber of Commerce try to take this model, can be said to be an unprecedented bold attempt, from the idea of construction to the real use, there will certainly be many twists and turns and difficulties, but after the completion, will bring different changes to the market of traditional Chinese medicine in Yulin City.	</p>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; In addition to the first opening of the sales index function, along with the rapid development of mobile Internet, it will further develop more functions, such as establishing a website platform, publishing supply and demand information on the Internet. Pharmaceutical companies can view the latest market information and supply and demand information on it, and even develop e-commerce in the future. Easy platform, pharmacists can directly complete online transactions, and business personnel can also rely on their own information and resources, online to facilitate bilateral transactions, more functions and conveniences, it is worth looking forward to. (Reporter Tao Jijun)	</p>
                                    <br>
                                    <br>
                                </span>
                                <span data-for="reco">
                                    <p style="color: #000;text-align: center;font-size: 3vh;font-weight: 550;margin-top: 2vh;line-height: 4vh;">Big Data of Beiliuli Agricultural Superior Products</p>
                                    <p style="margin-top: 2vh;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Beiliu agricultural products, Yulin news network Yulin evening news (reporter Liao Xiaodong) 4 morning, Beiliu County Internet + traceability system + precision poverty alleviation project launching ceremony held in the Beiliu municipal government. Beiliu City will establish a special quality and safety supervision and traceability system for agricultural products, and an intelligent quality and safety supervision and large data cloud platform with "production can be recorded, safety can be warned, source can be traced, flow can be traced, information can be stored, identity can be queried, responsibility can be identified, product can be recalled".</p>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;According to reports, a large number of pollution-free, green and organic agricultural production bases have been built in Beiliu City, and a number of famous Guangxi products such as Liangting Chicken and "Libao Brand" Chizuli have been cultivated. "In order to get products out and build cross-regional brands, we must improve the system, clarify the responsibility, and make the quality traceable and the responsibility accountable." The relevant person in charge of Beiliu City said that the establishment of "traceability system" would help to improve the quality of local agricultural products in Beiliu, thereby enhancing the competitiveness of products. Through the "traceability" project, consumers can scan the relevant information of products, promote the sale of Beiliu famous and excellent agricultural products, enhance the premium space of Beiliu products, and achieve enterprise efficiency and farmers'income.</p>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The person in charge said that all the relevant information left by the scanner records of the products sold can be analyzed through the background big data to provide reference for precise marketing. Big data can not only greatly improve the ability of local enterprises and farmers to predict the market and promote the adjustment of industrial institutions, but also help consumers understand the investment environment, folk culture, food, tourism and other information of Beiliu through scanning code, which is conducive to publicizing Beiliu and enhancing its popularity.</p>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Through this cooperation, Beiliu's high-quality products will further open up the national sales channels, upgrade the transformation of the combination of agricultural products and operators with the Internet, and further promote agricultural efficiency and farmers'income.</p>
                                    <br>
                                    <br>
                                </span>
                                <span data-for="theblog">
                                    <p style="color: #000;text-align: center;font-size: 3vh;font-weight: 550;margin-top: 2vh;line-height: 4vh;">"E-commerce + Poverty Alleviation" Passion Fruit Farmers Have Hope</p>
                                    <p style="margin-top: 2vh;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The unique natural conditions gave birth to the "fruits of wealth" of Beiliu people, Passion Fruit. In recent years, Beiliu City has made great efforts to regard Passion Fruit Industry as a local characteristic industry, a new industry and a superior industry, constantly strengthening and expanding. Passion fruit has won back brand names such as "China Passion Fruit Township", "Chinese Famous Fruit" and "China Consumer's Favorite (Fruit) Origin" for Beiliu. Small Passion Fruit holds up the "big industry" flowing north.</p>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Passion fruit has been planted in Beiliu city for 30 years, but the early development of Passion fruit industry is slow. With the advancement of Passion fruit industrialization and more people's understanding of its nutritional value, as well as with the development of network technology and logistics industry, Passion fruit industry in Beiliu has developed rapidly in recent years. The area under cultivation of fragrant fruits is 5333.33 hectares. Last year, the output reached more than 120,000 tons, and the sales revenue was more than 400 million yuan. From scientific research to seedling cultivation, to large-scale planting, to product acquisition, to e-commerce network marketing, to deep processing of fruits, Beiliu Passiflora has a relatively complete industrial chain. More and more farmers and entrepreneurs enter the "sweet" Passiflora cause, involving in Passiflora cultivation, e-commerce sales, juice processing, fresh pressed berries and plants. Flow, packaging and other industries, the formation of an amazing "Passion Fruit entrepreneurial group".</p>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;According to statistics, four large-scale fruit juice and beverage processing enterprises have been built in Beiliu City, producing more than 20,000 tons of fruit juice and beverage products annually, more than 10 kinds of deep-processing products of Passion fruit, including fruit juice, pulp, preserved fruit and jelly, 54 logistics express enterprises and 6 enterprises producing packaging and fresh-keeping materials and supplies. Last year, the sales of Passion Fruit in Beiliu E-commerce accounted for 70% of the country's total sales, and the share of Passion Fruit was the first in the country. This year, Beiliu E-commerce further broadened the sales scope and channels of Passion Fruit by means of activities such as "Passion Fruit E-commerce Culture Tourism Festival" and "Guangxi Specialty Marketing throughout the country". According to the statistics of Beiliu Express Company, in 2018, more than 10 million pieces of Passion Fruit Express were sent from Beiliu. The online sales of Passion Fruit from Beiliu accounted for 76% of the national sales. Beiliu has become the largest distribution center of Passion Fruit in China. Yang Xingzhong, general manager of Beiliu Dongyun Fruit Company, told reporters that their company's sales volume is about 25,000 kilograms per day, which has increased year on year. I believe Passion fruit will be very popular in the market in the future.</p>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Passion fruit was planted in the same year, yielding 800-1000 kg per mu in that year, 2000 kg per mu in normal year, and more than 10,000 yuan per mu in annual income. It has the advantages of low investment, quick effect and high benefit. Beiliu municipal governments at all levels and backing units for poverty alleviation take planting Passion Fruit as the main poverty alleviation industry. They present fruit seedlings and fertilizers to poor households, and give technical support to find a market to help poor households increase their income. In recent years, tens of thousands of farmers rely on the cultivation of Passion Fruit to become rich. Tan Jun, general manager of Beiliu Drunken Fruit Company, said that his company plans to raise 10 million seedlings this year, develop more growers to plant and get more Passion Fruit harvest.</p>
                                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In order to build a famous and high-quality brand of Passion Fruit in Beiliu, Beiliu City is currently embarking on the construction of a 10,000 Mu gold Passion Fruit core demonstration area, fully integrating Passion Fruit resources, building 333.33 hectares of high-quality, high-yield and high-efficiency Passion Fruit planting base in Xinrong and Min'an townships, and establishing 15 high-quality, high-yield and high-efficiency Passion Fruit demonstration sites from point to area. Focusing on the goal of "building a strong city of Passion Fruit Industry", we should accelerate the transformation and upgrading of Passion Fruit Industry, promote the optimization and upgrading of planting structure, and enhance the planting efficiency. At the same time, relying on the brand influence of "China Passion Fruit Township", Beiliu has done a good job in propaganda and promotion, attracting more funds to enter the construction of fruit industry chains such as Beiliu Passion Fruit, gradually building fruit production and processing centers in South China, and further strengthening the Passion Fruit industry. (Responsible Editor: Liu Ziyang)</p>
                                    <br>
                                    <br>
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
                    zw_click:0,
                }
            },
            head:{
                script:[
                {src:'js/jquery.1.7.1.min.js'},
                {src:'js/aos.js'},
                {src:'scripts/yl_app.js'},
            
                // 城市模块
                {src:'js/yl_jquery.min.js'},
    
                {src:'js/jquery-1.12.4.min.js'},
                {src:'js/popper.min.js'},
    
                // 产业模块
                {src:'js/yl_chanye/jquery-1.7.2.min.js'},
                {src:'js/yl_chanye/modernizr.custom.34807.js'},
                {src:'js/yl_chanye/demo.js'},

                
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
        // dialogClose(done){
        //     this.$confirm('确认关闭？')
        //       .then(_ => {
        //         done();
        //       })
        //       .catch(_ => {});
        // },
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