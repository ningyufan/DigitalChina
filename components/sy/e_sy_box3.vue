<template>
    <div class="sy_box3">
        <div class="sybox3_t" aos="zoom-in">
            Digital Person Interview
        </div>
        <div class="sybox3_con">
            <div class="options">
                <div class="option active">
                    <div class="shadow"></div>
                    <div class="label">
                        <div class="icon"> <i class="fas fa-walking"></i> </div>
                        <div class="info">
                            <div class="main">Liu Xinhua</div>
                            <div class="sub">Directors of Tangguan Group and Zhongshu Xin'an Group <span @click="sybox3_dialog1 = true">[Details]</span></div>
                        </div>
                    </div>
                </div>  
                <div class="option">
                    <div class="shadow"></div>
                    <div class="label">
                        <div class="icon"> <i class="fas fa-snowflake"></i> </div>
                        <div class="info">
                            <div class="main">Chen Sihua</div>
                            <div class="sub">Chairman and General Manager of Fujian Chenghua Credit Management, Ltd.<span @click="sybox3_dialog2 = true">[Details]</span></div>
                        </div>
                    </div>
                </div>
                <div class="option">
                    <div class="shadow"></div>
                    <div class="label">
                        <div class="icon"> <i class="fas fa-tree"></i> </div>
                        <div class="info">
                            <div class="main">Xiong Li</div>
                            <div class="sub">CEO of Netdragon Network Company<span @click="sybox3_dialog3 = true">[Details]</span></div>
                        </div>
                    </div>
                  </div>
                <div class="option">
                    <div class="shadow"></div>
                    <div class="label">
                        <div class="icon"> <i class="fas fa-tint"></i> </div>
                        <div class="info">
                            <div class="main">Lin Yongjun</div>
                            <div class="sub">General Manager of Yi Hualu<span @click="sybox3_dialog4 = true">[Details]</span></div>
                        </div>
                    </div>
                </div>
                <div class="option">
                    <div class="shadow"></div>
                    <div class="label">
                        <div class="icon"> <i class="fas fa-sun"></i> </div>
                        <div class="info">
                            <div class="main">Xiong Qunli</div>
                            <div class="sub">Chairman and Secretary of China Electronic Science and Technology Group, Ltd.<span  @click="sybox3_dialog5 = true">[Details]</span></div>
                        </div>
                    </div>
                </div>
                <div class="option">
                    <div class="shadow"></div>
                    <div class="label">
                        <div class="icon"> <i class="fas fa-sun"></i> </div>
                        <div class="info">
                            <div class="main">Zhang Guiping</div>
                            <div class="sub">Chairman of Suning Global Group<span  @click="sybox3_dialog6 = true">[Details]</span></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <el-dialog :visible.sync="sybox3_dialog1" width="60%">
          <template  slot="title">
              <div class="dia_title">
                The leader of the digital China dream--Liu Xinhua
              </div> 
            </template>
          <span>
            <video controls="controls" width="100%">
                <source src="https://flv2.bn.netease.com/videolib3/1802/04/YyHMo0057/SD/YyHMo0057-mobile.mp4" type="video/mp4">
            </video>
            
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sybox3_dialog1 = false">Return</el-button>
          </span>
        </el-dialog>
        <el-dialog :visible.sync="sybox3_dialog2" width="60%">
          <template  slot="title">
              <div class="dia_title">
                Chen Sihua
              </div> 
            </template>
          <span>
            <img src="../../assets/images/sy/sybox3_pic2.jpg" alt="">
            <p> 
                As China's digital economy enters the fast lane, big data is becoming an important way of credit data integration and credit services, and will gradually penetrate into the whole industry, breaking the island of information, Chen said.
                Finally, the data scattered in different government departments, industry organizations and social institutions are effectively integrated.
            </p><br/>
            <p> 
                "Comparing with the traditional way of credit information collection, big data credit collection adopts cloud computing service technology, that is, from the beginning of data entry to the output of evaluation results, the whole process is completed by computer algorithms.
                This avoids the influence of subjective judgment and ensures the accuracy of evaluation results. On this basis, the Internet and other information technologies based on the Internet, Chen said.
                It also provides a more efficient way for credit service. Even if we deal with multiple evaluation objects at the same time, we can still guarantee the accuracy and efficiency of credit evaluation. "Especially when the information of the respondents changes,
                Relying on big data, we can still calculate its credit quickly and timely to ensure the real-time of credit.
            </p>
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sybox3_dialog2 = false">Return</el-button>
          </span>
        </el-dialog>
        <el-dialog :visible.sync="sybox3_dialog3" width="60%">
          <template  slot="title">
              <div class="dia_title">
                Xiong Li
              </div> 
            </template>
          <span>
            <img src="../../assets/images/sy/sybox3_pic3.jpg" alt="">
            <p> 
                At the first Digital China Construction Summit, Netdragon Networks signed a strategic cooperation agreement with Peisheng Group. Xiong Li said that he hoped to use Netdragon's digital technology.
                Put the educational resources of Peyson, the world's largest offline education group, online step by step.
            </p><br/>
            <p> 
                "I think we are interoperable in teaching resources. Pei Sheng may have a bigger education market overseas, and we have done a lot of online and offline integration of educational resources at home. Our cooperation with Pei Sheng,
                It is hoped that the combination of the advantages of traditional offline resources and online resources can promote the whole process of digital education more effectively. Xiong Li further explained.
            </p><br/>
            <p> 
                Earlier in early April, Netdragon Networks acquired Edmodo, the world's leading learning community. Edmodo is one of the largest and most active learning community platforms in the world, with over 90 million registered users.
                Over 400,000 schools in 192 countries are a communication and collaboration platform for K-12 schools for teachers, students, managers and parents.
            </p><br/>
            <p> 
                Xiong Li said that he hoped that through this acquisition, he would make progress towards the goal of creating a lifelong learning platform, so that the educational products of Netdragon could be more comprehensive. As for whether it could go better in the next step, great efforts still need to be made.
            </p><br/>
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sybox3_dialog3 = false">Return</el-button>
          </span>
        </el-dialog>
        <el-dialog title="林拥军" :visible.sync="sybox3_dialog4" width="60%">
          <template  slot="title">
              <div class="dia_title">
                Lin Yongjun
              </div> 
            </template>
          <span>
            <img src="../../assets/images/sy/sybox3_pic4.jpg" alt="">
            <p> 
                Lin Yongjun said that the city data lake is to build a large data water infrastructure for the city, use optical storage technology to reduce the cost of data storage and energy consumption of data storage for the whole society, and more conducive to the development of large data industry.
                Lin Yongjun believes that the construction of data lake should be divided into three stages: building a large data warehouse in the lake, diverting social data resources to the lake, and exploiting and utilizing data resources.
            </p><br/>
            <p> 
                "The data lake is an infrastructure platform built by all of us. It keeps a large amount of data, opens it to enterprises and entrepreneurship teams, improves urban management and public services, and provides support for industrial transformation and upgrading.
                This model will greatly enrich the current big data industry. He said.
            </p><br/>
            <p> 
                In view of the significance of urban data lake to the construction of digital China, Lin Yongjun said that it would play a leading and basic supporting role. "In the future, every city will have its data lake, and the scale of the lake will be large or small.
                This will become the standard of urban development and provide comprehensive data storage services for regional development.
            </p><br/>
            <p> 
                When analyzing the relationship between data lake and cloud computing, Lin explained that many public cloud data centers focus on computing, emphasizing the priority of computing performance, which can be called thermal data. Thermal data is generated two weeks later.
                When the access frequency decreases, it becomes cold data. "Now there are both data lakes and clouds in a city. Clouds are responsible for processing thermal data and lakes for storing cold data. This will create a hot and cold ecology.
                He believes that the two will not replace each other, but constitute an ecological system together.。
            </p><br/>
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sybox3_dialog4 = false">Return</el-button>
          </span>
        </el-dialog>
        <el-dialog :visible.sync="sybox3_dialog5" width="60%">
          <template  slot="title">
              <div class="dia_title">
                We will accelerate the building of a new generation of information infrastructure to help develop digital China -- Xiong Qunli
              </div> 
            </template>
          <span>
            <img src="../../assets/images/sy/sybox3_pic5.jpg" alt="">
            <p> 
                Constructing Total Factor Perception System and Building Digital Service Platform
            </p><br/>
            <p> 
                The traditional information infrastructure does not include the perception layer. One thing that China Electrical Science has been doing in the past two years is to unify the perception of everything in the real world.
            </p><br/>
            <p> 
                How to unify? Xiong Qunli believes that the core is the unification of data level, that is, to sort out all data with unified standards, definitions and norms. Whether it's the perceived object temperature,
                Motion speed, shape, or motion process can be represented by data groups. When data are processed, fused and exchanged, data becomes a factor of production.
            </p><br/>
            <p> 
                Xiong Qunli believes that in order to build a new generation of information infrastructure, first of all, all parties must make further conceptual and cognitive progress. The new generation of information infrastructure is within the framework of a unified data standard system.
                Construct the perception system of all factors, break the information island, build a service platform based on big data, and realize the value-added application of perception, transmission, storage, development and artificial intelligence.
                Help the government to provide more valuable public services, and provide digital and intelligent information infrastructure and application support for the construction of digital China and intelligent society.
            </p><br/>
            <p> 
                In promoting demonstration applications, Xiong Qunli said that China Electrical Science and Technology has actively cooperated with local governments and industry departments, such as jointly launching pilot projects in Jiading District in Shanghai, and vigorously promoting the "Material, Digital, and Digital Couplings".
The construction of the three-in-one new metropolitan Federation of things special network promotes the digital transformation of cities and a new round of high-quality development.
            </p><br/>
            <p> 
                Broad Application Prospect of Big Data, Open Innovation and Digital Vitality
            </p><br/>
            <p> 
                Data is the core element of intelligent society, which has been integrated into daily life and become the basic resources in life.
            </p><br/>
            <p> 
                "Our country is at the forefront of the world in the application of big data." Xiong Qunli believes that although the application process of big data is long, it has broad prospects. The application of data should start from the industry, and analyze and process all relevant data related to the industry itself and the economy.
                Only in this way can we better help the government to provide more valuable public services and provide digital and intelligent information infrastructure for the construction of a wise society.
            </p><br/>
            <p> 
                Xiong Qunli said that the huge application demand is an important driving force for the innovation of big data application in China. At present, China is constantly exploring and innovating big data related applications, and has made some achievements in data utilization. He cited the application of big data in Guizhou as an example.
                Using big data to find casualties in a landslide section on the highway, no matter what vehicle or personnel, can be found quickly with the support of big data.
            </p><br/>
            <p> 
                　Xiong Qunli said that the concept and understanding of China's development of big data are advanced, and the idea of putting forward digital economy is forward-looking. However, there are still some gaps in basic data algorithms and tools when it comes to big data technology. He suggested that we should stimulate the vitality of scientific researchers through reform.
                Through international cooperation, the introduction of digestion and absorption of new technologies will promote the innovation and development of big data and stimulate the innovation vitality of digital society.
            </p><br/>
            <p> 
                Strengthening Basic Scientific Research and Constructing a New Generation of Information Infrastructure
            </p><br/>
            <p> 
                Electronic information technology is closely related to modern science and has made important contributions to the development of national economy. Although China has been in the forefront of the application field, it still needs to further solve the "sticking neck" problem in key areas.
            </p><br/>
            <p> 
                Xiong Qunli believes that the basic research fields of electronic information technology in China are relatively weak. In the future, we should increase investment in scientific research and innovation, and achieve overall layout and overall planning in the basic research fields.
            </p><br/>
            <p> 
                Specifically for China Science and Technology, Xiong Qunli said that in recent years, enterprises have increased their layout in the basic areas, and even entered the research of materials, underlying science and technology. In addition, the systematic layout of China Electrical Science has been continuously strengthened. "Although we are a group, each member unit has its own research direction.
                In terms of scientific research content, we should strengthen internal integration, form a system and form a system. Xiong Qunli said that under the guidance of this idea, China Electrical Technology has set a goal for itself, hoping to become the world's first-class innovative leader by the middle of this century.
            </p><br/>
            <p> 
                　Speeding up the construction of a new generation of information infrastructure will play a positive role in enhancing people's well-being. Xiong Qunli said that in the future, China Electricity will continue to actively participate in the construction of a new generation of information infrastructure in accordance with the deployment of the Party Central Committee and the State Council.
            </p><br/>
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sybox3_dialog5 = false">Return</el-button>
          </span>
        </el-dialog>
        <el-dialog title="张桂平--数字经济和新消费成为经济发展新引擎" :visible.sync="sybox3_dialog6" width="60%">
           <template  slot="title">
              <div class="dia_title">
               The digital economy and new consumption have become new engines of economic development -- Zhang Guiping
              </div> 
            </template>
          <span>
            <img src="../../assets/images/sy/sybox3_pic6.jpg" alt="">
            <p> 
                The following are the main contents of the interview:
            </p><br/>
            <p> 
                Moderator: You mentioned that vigorously developing digital economy is the current hot spot of the proposal. Can you start to talk about your views on digital economy?
            </p><br/>
            <p> 
                Zhang Guiping: Digital economy is a new economic form, which has penetrated into all economic links. Promoting the vigorous development of digital economy has become a new driving force for economic growth. At present, the development of digital economy in China has followed.
                It has been gradually transformed into a leader, but there are still some problems, such as unbalanced development, high barriers to digital transformation of enterprises and insufficient supporting capacity of digital transformation services. Therefore, in my proposal, I suggest that:
                Firstly, we should promote industrial digital transformation by government digital transformation; secondly, we should provide a good environment for the development of digital economy; thirdly, we should promote the upgrading of service ecological form through innovation and service capacity enhancement. In my submission,
                To overcome these problems, China's digital economy will surely reach a new level.
            </p><br/>
            <p> 
                　Moderator: We have noticed that you have also paid attention to a relatively new concept in this proposal, namely, the development of new consumption. Could you give us a brief introduction?
            </p><br/>
            <p> 
                Zhang Guiping: Nowadays, new consumption patterns emerge endlessly in practice and gradually become the new engine of economic development. It is very important to build a new consumption ecosphere and its own system in the whole time and space for the development of new consumption.
                Of course, there are still some problems in the new consumption field in China, such as inaccurate grasp of the concept of new consumption by enterprises, and obscure display of Chinese cultural elements.
            </p><br/>
            <p> 
                　In terms of new consumption, I also have some suggestions. First, we should formulate relevant planning policies and measures, establish cross-sectoral promotion mechanism, and guide marketing interaction through big data science.
            </p><br/>
            <p> 
                Secondly, we should establish a new system of consumer service standards, focus on improving service levels, and strengthen the guidance to standardize and standardize the development of key areas such as pension, education, medical treatment and health.
            </p><br/>
            <p> 
                Thirdly, we should tell Chinese stories well, gather resources well, integrate across borders, link brands, and use culture to satisfy people's pursuit of quality of life.
            </p><br/>

          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sybox3_dialog6 = false">返 回</el-button>
          </span>
        </el-dialog>

    </div>
</template>

<script>
export default {
  data() {
    return {
      sybox3_dialog1:false,
      sybox3_dialog2:false,
      sybox3_dialog3:false,
      sybox3_dialog4:false,
      sybox3_dialog5:false,
      sybox3_dialog6:false,
    }
  }
}
</script>

<style>
.sy_box3{
  width: 100vw;
  height: 100vh;
  /* background-color: aqua; */
}
.sybox3_t{
  font-size: 6vh;
  font-family: STXingkai;
  color: rgb(48, 189, 245);
  z-index:5;
}
.sybox3_t:hover{
  animation: sybox3_t 1s linear 3;
}

@keyframes sybox3_t{
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

.sy_box3 .sybox3_con {
  width: 80vw;
  height: 75vh;
  margin:0 auto;
}
/* sybox3手风琴效果 start */
.options {
  display: flex;
  flex-direction: row;
  align-items: stretch;
  overflow: hidden;
  min-width: 80vw;
  max-width: 80vw;
  width: calc(100% - 100px);
  height: 70vh;
  margin:0 auto;
  margin-top:5vh;
}

@media screen and (max-width: 718px) {
  .options {
      min-width: 520px;
  }

  .options .option:nth-child(5) {
      display: none;
  }
}

@media screen and (max-width: 638px) {
  .options {
      min-width: 440px;
  }

  .options .option:nth-child(4) {
      display: none;
  }
}

@media screen and (max-width: 558px) {
  .options {
      min-width: 360px;
  }

  .options .option:nth-child(3) {
      display: none;
  }
}

@media screen and (max-width: 478px) {
  .options {
      min-width: 580px;
  }

  .options .option:nth-child(2) {
      display: none;
  }
}

.options .option {
  position: relative;
  overflow: hidden;
  min-width: 60px;
  margin: 10px;
  background: var(--optionBackground, var(--defaultBackground, #E6E9ED));
  background-size: auto 120%;
  background-position: center;
  cursor: pointer;
  transition: 0.5s cubic-bezier(0.05, 0.61, 0.41, 0.95);
}

.options .option:nth-child(1) {
  --defaultBackground: #ED5565;
  background-image: url(../../assets/images/sy/sybox3_pic1.jpg);
  
}

.options .option:nth-child(2) {
  --defaultBackground: #FC6E51;
  background-image: url(../../assets/images/sy/sybox3_pic2.jpg);

}

.options .option:nth-child(3) {
  --defaultBackground: #FFCE54;
  background-image: url(../../assets/images/sy/sybox3_pic3.jpg);

}

.options .option:nth-child(4) {
  --defaultBackground: #2ECC71;
  background-image: url(../../assets/images/sy/sybox3_pic4.jpg);
}

.options .option:nth-child(5) {
  --defaultBackground: #5D9CEC;
   background-image: url(../../assets/images/sy/sybox3_pic5.jpg);
}

.options .option:nth-child(6) {
  --defaultBackground: #AC92EC;
  background-image: url(../../assets/images/sy/sybox3_pic6.jpg);
}

.options .option.active {
  flex-grow: 10000;
  -webkit-transform: scale(1);
  transform: scale(1);
  max-width: 800px;
  margin: 0px;
  border-radius: 40px;
  background-size: auto 100%;
  /*&:active {
   transform:scale(0.9);
}*/
}

.options .option.active .shadow {
  box-shadow: inset 0 -120px 120px -120px black, inset 0 -120px 120px -100px black;
}

.options .option.active .label {
  bottom: 4vh;
  left: 4vh;
}

.options .option.active .label .info>div {
  left: 0px;
  opacity: 1;
}

.options .option:not(.active) {
  flex-grow: 1;
  border-radius: 30px;
}

.options .option:not(.active) .shadow {
  bottom: -40px;
  box-shadow: inset 0 -120px 0px -120px black, inset 0 -120px 0px -100px black;
}

.options .option:not(.active) .label {
  bottom: 10px;
  left: 10px;
}

.options .option:not(.active) .label .info>div {
  left: 20px;
  opacity: 0;
}

.options .option .shadow {
  position: absolute;
  bottom: 0px;
  left: 0px;
  right: 0px;
  height: 120px;
  transition: 0.5s cubic-bezier(0.05, 0.61, 0.41, 0.95);
}

.options .option .label {
  display: flex;
  position: absolute;
  right: 0px;
  height: 5vh;
  transition: 0.5s cubic-bezier(0.05, 0.61, 0.41, 0.95);
}

.options .option .label .icon {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  min-width: 4vh;
  max-width: 4vh;
  height: 4vh;
  border-radius: 100%;
  background-color: white;
  color: var(--defaultBackground);
}

.options .option .label .info {
  display: flex;
  flex-direction: column;
  justify-content: center;
  margin-left: 1vw;
  color: white;
  white-space: pre;
}

.options .option .label .info>div {
  position: relative;
  transition: 0.5s cubic-bezier(0.05, 0.61, 0.41, 0.95), opacity 0.5s ease-out;
}

.options .option .label .info .main {
  line-height: 6vh;
  font-size: 4vh;
}

.options .option .label .info .sub {
   line-height:3.75vh;
  font-size: 2.5vh;
}
/* sybox3手风琴效果 end */

.dia_title {
  font-size: 4vh;
  line-height: 6vh;
}
p {
  font-size: 3vh;
  line-height: 4.5vh;
  text-indent: 2rem;
}
</style>