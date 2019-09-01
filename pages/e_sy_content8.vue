<template>
    <div class="sy_content8">
        <div class="sycon8_t">
            5G loud voice
        </div>
        <div class="sycon8_info">
            <div class="sycon8_infobg">
                <img src="../assets/images/sy/sycon8_bg.png" alt="">
            </div>
            <div class="sycon8_box1" aos = "fade-right" >
                <div class="sycon8_box1_t">How is 5G standard formulated?</div>
                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The 5G standard is composed of many technologies, and coding is a very basic technology. At one time, there was a heated debate on channel coding standards among the major camps in the world.<span  @click="sycon8_dialog1 = true">[details]</span></p>
            </div>
            <div class="sycon8_box2" aos = "fade-left" aos-delay = "300">
                <div class="sycon8_box1_t">5G commercial annual revenue will exceed trillion</div>
                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;In 2020, the first full commercial use of 5G will bring about a huge indirect income of about 120 billion yuan.<span  @click="sycon8_dialog2 = true">[details]</span></p>
            </div>
            <div class="sycon8_box3" aos = "fade-right" aos-delay = "600">
                <div class="sycon8_box1_t">Millimeter Wave Solves 5G Big Problem</div>
                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Standard landing, commercial sprint. However, on the road of 5G, the shortage of spectrum resources has become a major obstacle.<span  @click="sycon8_dialog3 = true">[details]</span></p>
            </div>
            <div class="sycon8_box4" aos = "fade-left" aos-delay = "900">
                <div class="sycon8_box1_t">5G Communications Expected to be Commercial in 2020</div>
                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;At the 2018 World Mobile Conference, the three major operators and a number of enterprises in the industry chain have issued the latest 5G deployment plan.<span  @click="sycon8_dialog4 = true">[details]</span></p>
            </div>
            <div class="sycon8_box5" aos = "fade-right" aos-delay = "1200">
                <div class="sycon8_box1_t">5G≠4G+1G</div>
                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5G Communications Expected to be Commercial in 2020<span  @click="sycon8_dialog5 = true">[details]</span></p>
            </div>
            <div class="sycon8_box6" aos = "fade-left" aos-delay = "1500">
                <div class="sycon8_box1_t">This "black technology" may bring 5G mobile phones out half a year ahead of schedule.</div>
                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Recently, Qualcomm has launched the world's first fully integrated 5G NR millimeter wave and below 6GHz radio frequency module for smartphones and other mobile terminals.<span  @click="sycon8_dialog6 = true">[details]</span></p>
            </div>
        </div>

        <el-dialog title="How is 5G standard formulated?" :visible.sync="sycon8_dialog1" width="60%">
          <span>
               <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                The 5G standard is composed of many technologies, and coding is a very basic technology. Among the 5G related standards, there was a heated debate on channel coding standards among the world's major camps at one time. In 2016,
Polar, which is pushed by Chinese telecommunications companies, becomes the control channel coding. This is the first breakthrough in the field of channel coding in China and lays the foundation for China to strive for more voice rights in 5G standard than before.
"From this point of view, China can be said to be in the forefront of the world to a certain extent."
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                From May 21 to 25, the International Organization for Standardization of Mobile Communications (ISO) 3GPP Working Group held the last meeting of the 5G first stage standard-setting in Busan, South Korea. It is reported that,
This meeting will determine the full content of the 3GPP R15 standard. It is expected that at the plenary meeting in the United States next month, 3GPP will announce the first phase of the 5G standard.
So, what kind of organization is 3GPP responsible for Telecom standards? How is the widely concerned 5G standard formulated? How much voice do Chinese enterprises have in the process of formulating 5G standards?
With these problems, Beijing Youth Daily reporters interviewed people in the industry.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;                
                <b>The 5G Independent Networking Standard is expected to be released and established next month.</b>
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                At this 3GPP Busan conference, all the working groups that develop 5G wireless technology will gather at this meeting to finalize the relevant standard technologies for the commercialization of 5G RAN.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                About 1500 Standard experts from chipsets, mobile phone and equipment suppliers and mobile operators will attend the meeting to complete the first phase of 5G standard.
It includes 5G wireless access technology providing ultra-high-speed data and ultra-low latency, and conformance testing methods for 5G terminals. In short, after the Busan Conference,
In the first phase of 5G, the standard of independent networking is coming out soon.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                Several Chinese enterprises, including Huawei, OPPO, VIVO and other communication equipment and mobile phone manufacturers, also participated in the discussion and submitted proposals. Yang Chaobin, president of Hua5G product line, said that as planned,
The meeting will complete the standard technology for 5G Independent Networking (SA), which will be officially announced at next month's U.S. plenary meeting, and Huawei has prepared a proposal. After the standard has been determined,
Equipment companies have standard-based equipment for commercial use.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                Previously, 3GPP determined that 5G standardization was divided into two stages: the first stage started with R15 as 5G standard, which was completed in June 2018; the second stage started with R16 as 5G standard, which was completed in December 2019.
The first phase of 5G will be finalized at the 3GPP conference in the United States next month.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                <b>How many 5G standards are there?</b>
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                Some readers can't help wondering, didn't last year say that 3GPP has established a 5G standard? How can we confirm it again now? Why is there any argument that the final standard will wait until 2019, or even 2020?
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
               "The last time we determined the non-independent networking standard, this time we will determine the 5G independent networking standard." Senior communications observer Xiang Ligang pointed out in an interview that non-independent networking, in short, is not an independent 5G network.
Integrating with other things, such as networking with 4G or even 3G, and 5G independent networking means that there is no 4G, a fully established 5G network.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                "In non-independent networking, what about 5G? 5G as a supplement, the big network is 4G, but in some hot areas, such as Olympic venues, CBD and so on, these local areas increase hotspots through 5G to improve network speed and user perception and experience.
But the whole network is still not 5G. By contrast, 5G independent networking means that the entire network is completely covered by 5G. Xiang Ligang further explained.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                　"The establishment of independent networking standards means that the deployment standards of 5G network have tended to be perfect," said Xiang Ligang. The core of non-independent networking is hotspot, which solves the problem of local hotspot coverage on a small scale.
The 5G comprehensive network coverage problem can be solved, so the establishment of the standard is very important. We can think that the 5G standard is further improved.
            </p><br/>
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sycon8_dialog1 = false">Return</el-button>
          </span>
        </el-dialog>

        <el-dialog title="5G commercial annual revenue will exceed trillion" :visible.sync="sycon8_dialog2" width="60%">
          <span>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              In 2020, the first full commercial use of 5G will bring about a huge indirect income of about 120 billion yuan. Reporters learned yesterday that mobile 5G packages are expected to contain 10 times more traffic than today, and will allow cable broadband and WiFi to "retire".
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              At the World Mobile Internet Conference, Huang Yuhong, Vice President of China Mobile Research Institute, disclosed that China's Internet of Things has more than 380 million connections, and 5G will bring an extremely broad market. It is estimated that besides the revenue of operators, 5G will achieve an indirect income of 120 billion yuan for the first time in 2020, 2.3 trillion yuan in 2021 and 4 trillion yuan in 2022. For the future development of digital economy, 5G will become an important foundation. Huang Yuhong introduced that China Mobile has not only established 5G joint innovation center.
Fourteen open laboratories have also been built throughout the country, and a 5G venture fund will be launched to support 5G innovation and entrepreneurship.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
               Li Yuguang, General Manager of Public Traffic Division of China Telecom Integrated Platform, boldly predicted at the meeting that with the development of 5G network, its advantages of high speed and high bandwidth will directly suppress the use of wired broadband and WiFi. In the 5G era, it is expected that the area of cable broadband will gradually shrink until it disappears.
            </p><br/>
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sycon8_dialog2 = false">Return</el-button>
          </span>
        </el-dialog>

        <el-dialog title="Millimeter Wave Solves 5G Big Problem" :visible.sync="sycon8_dialog3" width="60%">
          <span>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             Standard landing, commercial sprint. However, on the road of 5G, the shortage of spectrum resources has become a major obstacle.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             Compared with any previous generation of communication systems, 5G needs to meet more diverse scenarios and extreme performance challenges, so it is necessary to lay out the candidate bands supporting the new 5G standard in full band. However, the low band is already extremely crowded, and most of them involve interference protection with other systems. In most parts of the world, the most direct way is to use frequency bands with high frequencies.
Including the left and right bands of 3GHz below 6GHz and millimeter-wave bands above 24GHz, these bands have more available bandwidth than low-frequency bands.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             In the process of searching for new spectrum resources, China is also facing an unprecedented shortage of spectrum resources. Before 4G, the high quality frequencies in the low frequency band had been gradually consumed, so China took the lead in dividing the low frequency band for 5G. According to the planning, the resources in the 5G band in China mainly concentrated in the 3.5GHz and 4.8GHz bands.
Millimeter wave, which has been paid much attention before, is still in the stage of seeking advice, and it is expected to make progress.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             At the recently concluded 5G and future network strategy seminar, Chen Lidong, deputy director of the Communications Development Department of the Ministry of Industry and Information Technology, requested that the research on the evolution of mobile communication air port technology, millimeter wave and other new technology fields be strengthened. The 5G Microwave and Millimeter Wave Technology Task Force specially established by the Future Mobile Communication Technology and Standard Development Promotion Committee,
A white paper on 5G millimeter wave spectrum planning was issued, calling for the urgent need to define the 5G spectrum layout in millimeter wave and to establish the available frequency band as soon as possible. 24.75-27.5 GHz and 37-42.5 GHz should be planned as soon as possible to give clear guidance to the industry. It is suggested that the frequency planning should be completed by the end of 2018 to support the 2019 millimeter wave pre-commercial test and 202.5 GHz. Millimeter wave large-scale commercial deployment in the past 10 years.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             In fact, in our country, millimeter wave technology is not a technology that has never been involved before. In this regard, Qualcomm has a profound experience in the United States, which has made an important contribution to the above white paper. Xu Xu, head of R&amp;D in China, said that through exchanges with many Chinese manufacturers and partners, it was found that:
The accumulation of millimeter wave technology in China is not weak. Many research institutes and universities have accumulated relevant research, and also have a certain degree of application in base station technology. "In fact, millimeter wave technology has been applied in many fields, and we need to promote this technology to a wider range of commercial applications."
Reporters learned that at the technical support level, including multi-antenna technology, broadband automatic processing capabilities, China has a certain technical reserve as the basis of millimeter-wave technology, may first use less than 6 GHz band technology. At present, many Chinese operators and manufacturers are actively promoting the application of millimeter wave technology in this frequency band.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             Looking at the world, millimeter wave planning is the general trend. At present, in the frequency band below 6GHz, we can see that the frequency band of 3GHz has attracted worldwide attention. Many countries around the world are dividing or planning to divide the millimeter wave band above 24 GHz. In July 2016, the United States divided millimeter-wave spectrum up to 11 GHz into 5 G bands.
Other regions, including Europe, Korea, Japan, Australia and Canada, are also dividing the millimeter wave spectrum for 5G. In some cases, part of the millimeter wave spectrum may be divided into shared or unauthorized spectrum rather than authorized spectrum, which may be necessary in certain circumstances.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             "There is no doubt that the millimeter wave spectrum is crucial for 5G in China and around the world. Millimeter-wave bandwidth can provide extreme bandwidth, so it is essential to meet the needs of better and faster enhanced mobile broadband, and compared with the current Gigabit LTE services in China and other parts of the world.
The millimeter wave band can provide significant difference for 5G. Xu thinks so.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             This importance is evident in the comparative data of a series of tests. In this regard, Qualcomm has conducted a series of 5G real network simulation experiments. A 5G network simulation experiment was carried out in San Francisco, USA. With the existing LTE base station supplemented by millimeter wave capacity, the network capacity gain is five times. At the same time, when the 4G coverage reaches 100%.
By adding millimeter wave to existing 4G base stations, 65% coverage of 5G network can be achieved. Another group of experiments in Frankfurt is the simulation experiment of conversion from 4 G to 5 G on the spectrum below 6 GHz. As far as download rate is concerned, the gain is 8.8 times from 56 Mbps of 4 G user average to 490 Mbps of 5 G user average, and 9.2 times from cell edge burst data.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            Thanks to the results of the experiment, Qualcomm has developed and demonstrated a test platform using two frequency bands below 6GHz and millimeter wave, and introduced a 5G modem MX50 which can support the operation of new holes below 6GHz and millimeter wave bands.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             As for the challenge of millimeter wave, Xu also admitted, "It is easier to cause path obstruction and signal attenuation by using millimeter wave band transmission. Therefore, the efficiency and robustness of millimeter wave signal transmission is one of our research and development priorities. In addition, it is also high-pass for how to make millimeter wave technology better adapt to terminal size and power consumption. Technical research direction." (Nash)
            </p><br/>
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sycon8_dialog3 = false">Return</el-button>
          </span>
        </el-dialog>

        <el-dialog title="5G Communications Expected to be Commercial in 2020" :visible.sync="sycon8_dialog4" width="60%">
          <span>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             At the 2018 World Mobile Congress recently held, the three major operators in China's mobile communication field and several enterprises in the industry chain have issued the latest 5G deployment plan, clearly realizing the formal commercial use of 5G by 2020.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             According to the plan of Ministry of Industry and Information Technology, China's 5G test will be divided into two steps: the first step is from 2016 to the end of 2018, the 5G technology R&amp;D test, the main goal is to participate in supporting the formulation of 5G international standards; the second step is from 2018 to the end of 2020, the 5G product R&amp;D test, the main goal is to carry out 5G pre-commercial test. According to this timetable, the industry agrees that:
China is expected to achieve 5G pre-commercial communications in 2019 and large-scale formal commercialization of 5G communications in 2020.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
            Lu Yimin, general manager of China Unicom Network Communications Group Co., Ltd., said that in the 5G field, China Unicom has launched 5G scale tests in 16 cities, and will demonstrate and test its business application in 2019, and plan to formally commercialize in 2020.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             Shang Bing, chairman of China Mobile Communications Group Co., Ltd., said that China Mobile will vigorously promote 5G scale test and application demonstration, strive for scale test in 2018, achieve pre-commercial in 2019 and achieve full commercial in 2020.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             In order to achieve the goal of officially commercializing 5G by 2020, the commercial pace of the whole industrial chain is accelerating. Especially the 5G independent networking standard has just been frozen recently, which means that the first stage of full-function standardization of 5G has been completed and released, and has entered the stage of full-scale industrial sprint.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             China Unicom said that its 5G network will be based on independent networking standards, focusing on enhancing mobile broadband in the early stage, maintaining its network speed advantages in the 3G and 4G era, providing a full range of high-volume and high-bandwidth applications such as high-definition video, virtual reality/augmented reality game entertainment, car-borne video, intelligent home and so on. Network support.
In the follow-up, we will actively introduce low-latency, high-reliability and mass machine-based communication technologies to support the digital transformation of vertical industries such as vehicle networking and industrial internet, in combination with technological standards and the development process of ecosystems.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             During the World Mobile Congress in 2018, China Mobile jointly launched "5G SA (Independent Networking) Initiative" with global partners such as Datang Telecom, Ericsson, Huawei, Intel and Nokia, aiming at promoting independent networking from standard to real commercialization and promoting end-to-end product maturity as soon as possible.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             During the conference, Yang Xiaowei, deputy director of CNN Information Office, and Shanghai Mobile Technologists conducted the first 5G independent end-to-end system holographic video calls in the world. For the first time, 5G independent end-to-end system technology was used in the calls, which marked a breakthrough in 5G independent network technology and the development of 5G industry was accelerating.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             Earlier, China Mobile also released 12 5G innovations to the outside world. Li Zhengmao, Vice President of China Mobile Communications Group Co., Ltd., formally awarded licences to three open laboratories in Jiangsu, Hubei and Guizhou. At present, China Mobile 5G Joint Innovation Center has 224 industrial partners in the United States.
Sweden and China have set up 14 open laboratories and cooperated with dozens of 5G innovative projects.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             Shang Bing said that China Mobile should plan 5G network with the goal of independent networking, promote the cloud deployment of 5G network, accelerate the end-to-end maturity of 5G industry, relying on 5G joint innovation center and 5G industry research institute, develop innovative platforms and R&amp;D applications such as smart cities, vehicle networking, industrial Internet, etc.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             China Telecom released "China Telecom 5G Technology White Paper" the day before the 2018 World Mobile Congress, which is the first white paper issued by global operators to comprehensively expound 5G technology viewpoints and overall strategy.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             Liu Aili, general manager of China Telecom Group Limited, said that China Telecom will make every effort to promote 5G development from two aspects of technological innovation and industrial cooperation. As far as technological innovation is concerned, by the end of June 2018, China Telecom has led 31 projects and tasks of 5G international standards and submitted 457 international manuscripts.
190 technical patents have been applied for, of which 143 have been granted patent protection. In terms of industrial cooperation, China Telecom launched the construction of 5G innovation demonstration network in six cities, such as Xiongan, and opened all 5G pilot base stations in December 2017; in February 2018,
The National Development and Reform Commission formally approved China Telecom to carry out 5G scale construction and application demonstration projects in 12 cities such as Beijing.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             The 5G terminal product guide issued by China Mobile during the conference shows that the first batch of 5G chips will be launched at the end of 2018, the first batch of 5G terminals will be launched in the first quarter of 2019, and the 5G smartphones will be launched in the third quarter of 2019. China Mobile also has 28 members of the 5G Terminal Pioneer Program.
Including 6 mainstream chip enterprises, 13 mainstream terminal enterprises, 5 component enterprises and 4 instrument enterprises, signed a memorandum of cooperation to accelerate the development of 5G terminal industry and incubate products.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             Obviously, according to this schedule, terminal manufacturers also need to speed up. Xu Zhijun, Chairman-in-Office of Huawei, said that Huawei would launch 5G commercial system based on independent networking standards on March 30, 2019, Kirin chips supporting 5G in 2019 and smartphones supporting 5G in June, 2019.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             Kristiano Amon, president of Qualcomm, also said that the 5G data terminal will be released in some markets in December, and the first smartphones with full 5G functions will be launched by the affiliated factories with Qualcomm in March and April next year.
            </p><br/>
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sycon8_dialog4 = false">Return</el-button>
          </span>
        </el-dialog>

        <el-dialog title="5G≠4G+1G" :visible.sync="sycon8_dialog5" width="60%">
          <span>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             As a new generation of communication technology, 5G is coming to us. What areas will 5G commerce promote?
A few days ago, academics and industry experts gave answers to the "Accelerating the Road to 5G" industry salon held in Intel (China).
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             Wu Geng, chief technical expert of wireless standards in Intel (China) Communications and Equipment Business Department, said that 5G is not only a simple addition of 1G to 4G, but also brings not only faster transmission rate and higher network bandwidth, but also ultra-high reliability and low latency.
In the future, unmanned driving, virtual reality, smart city and other fields will release huge potential due to 5G.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             "In the 5G era, people and people, people and things, things and things will be integrated, and a new information infrastructure will be built." Xu Zhiyuan, deputy director of the Institute of Integration of Informatization and Industrialization of China Information and Communication Research Institute, said. He said that some of the current applications,
For example, the high reliability and low latency required by driverless vehicles can not be met by 4G. The emergence of 5G will bring a good user experience for driverless vehicles.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             Wu Geng introduced that 5G can achieve a delay of less than 1 millisecond and a peak transmission rate of up to 10G BPS (bit per second). Ultra-low latency and high-speed transmission of large data files enable 5G to acquire information about its surroundings in almost real-time like Sixth Sense.
Vehicles can use cloud-based artificial intelligence and data to "communicate" in real time with other vehicles on the road and traffic infrastructure, including street lights.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             Virtual reality will change the way people perceive reality. Xu Zhiyuan said that from computing to sensing, especially in communications, virtual reality is not ready to provide users with a good experience. 5G will greatly improve the experience of virtual reality.
And make ubiquitous real-time video sharing, anytime, anywhere cloud access and so on will become a reality.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             Globally unified standards can lay a solid foundation for the future development of 5G. Under the globally unified standard, both Chinese and European intelligent devices can be connected normally, which can not only reduce costs, but also bring great convenience to users.
Because the previous 2G, 3G and 4G systems mainly serve communication, there is a multi-standard parallel situation. Luo Zhendong, an expert of the fifth generation mobile communication technology promotion group of the Ministry of Industry and Information Technology, said that after entering the 5G era, the market will usher in a "real sense of convergence network".
Including China, all countries in the world are striving to achieve 5G standardization in the global scope.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             China has launched the 5G technology R&amp;D test in an all-round way, and China's 5G test is also the first national 5G test led and planned by the government in the world. Verizon, an American telecommunications operator, announced this year that it will carry out a 5G pilot operation in 11 cities in the United States. The second phase of the 5G network test in China is also planned to be officially launched this year.
It is generally expected that the standardized 5G network will be commercially available around 2020.
            </p><br/>            
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sycon8_dialog5 = false">Return</el-button>
          </span>
        </el-dialog>

        <el-dialog title="This 'black technology' may bring 5G mobile phones out half a year ahead of schedule." :visible.sync="sycon8_dialog6" width="60%">
          <span>
            <img src="../assets/images/sy/sycon8_pic1.jpg" alt="">
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             Recently, Qualcomm has launched the world's first fully integrated 5G NR millimeter wave and below 6GHz radio frequency module for smartphones and other mobile terminals. These two RF modules support millimeter wave and below 6GHz respectively.
It can adapt to different frequency bands of different operators in different regions. Industry insiders believe that the successful development of the key "black technology" for 5G mobile phones will enable mobile phone manufacturers to launch 5G mobile phones at least half a year in advance and accelerate global 5G commerce.
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             This millimeter-wave 5G radio frequency module can work with the X50 5G modem and form a complete system to meet the huge challenges of millimeter-wave. As a complete system, it can support advanced beam forming, beam steering and beam tracking technologies.
The coverage and reliability of millimeter wave signal are improved significantly. More importantly, Qualcomm's 5G RF module is exquisite and compact in size, which can be described as a module on the fingertips. Mobile phone manufacturers can easily integrate it into mobile phones.
In this way, the manufactured mobile phone can keep its appearance and thickness as close as possible to that of the 4G mobile phone. (Correspondent Diao Xingling, reporter Li Liyun)
            </p><br/>
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sycon8_dialog6 = false">Return</el-button>
          </span>
        </el-dialog>
    </div>
</template>

<script>
export default {
    layout: 'e_content2',
    data() {
        return {
            sycon8_dialog1: false,
            sycon8_dialog2: false,
            sycon8_dialog3: false,
            sycon8_dialog4: false,
            sycon8_dialog5: false,
            sycon8_dialog6: false,

        }
    }
}
</script>

<style>
.sycon8_t {
    height: 10vh;
    width: 100%;
    line-height: 10vh;
    font-size: 5vh;
    text-align: center;
    color: rgb(48, 189, 245);
    /* background-color: beige; */
    background-image: url(../assets/images/sy/sycon5_bgb.png);
    background-size: 100% 100%;
}
.sycon8_info {
    height: 140vh;
    width: 100%;
   position: relative;
    color: white;
}
.sycon8_infobg {
    position: absolute;
    top: 30vh;
    left: 23vw;
    width: 100%;
}
.sycon8_info .sycon8_box1_t {
    line-height: 10vh;
    font-weight: bold;
}
.sycon8_info .sycon8_box1 {
    height: 25vh;
    width: 23vw;
    position: absolute;
    top: 15vh;
    left: 0;
    background-color: rgba(0, 0, 0, 0.2);
}
.sycon8_info .sycon8_box2 {
    height: 25vh;
    width: 23vw;
    position: absolute;
    top: 15vh;
    right: 0;
    background-color: rgba(0, 0, 0, 0.2);
}
.sycon8_info .sycon8_box3 {
    height: 25vh;
    width: 23vw;
    position: absolute;
    top: 45vh;
    left: 0;
    background-color: rgba(0, 0, 0, 0.2);
}
.sycon8_info .sycon8_box4 {
    height: 25vh;
    width: 23vw;
    position: absolute;
    top: 45vh;
    right: 0;
    background-color: rgba(0, 0, 0, 0.2);
}
.sycon8_info .sycon8_box5 {
    height: 25vh;
    width: 23vw;
    position: absolute;
    top: 75vh;
    left: 0;
    background-color: rgba(0, 0, 0, 0.2);
}
.sycon8_info .sycon8_box6 {
    height: 25vh;
    width: 23vw;
    position: absolute;
    top: 75vh;
    right: 0;
    background-color: rgba(0, 0, 0, 0.2);
}
</style>