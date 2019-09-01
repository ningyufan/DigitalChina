<template>
    <div class="sy_box3">
        <div class="sybox3_t">
            数字人物访谈
        </div>
        <div class="sybox3_con">
            <div class="options">
                <div class="option active">
                    <div class="shadow"></div>
                    <div class="label">
                        <div class="icon"> <i class="fas fa-walking"></i> </div>
                        <div class="info">
                            <div class="main">刘欣华</div>
                            <div class="sub">唐冠集团、中数信安集团董事 <span @click="sybox3_dialog1 = true">[详情]</span></div>
                        </div>
                    </div>
                </div>  
                <div class="option">
                    <div class="shadow"></div>
                    <div class="label">
                        <div class="icon"> <i class="fas fa-snowflake"></i> </div>
                        <div class="info">
                            <div class="main">陈思华</div>
                            <div class="sub">福建诚华信用管理有限公司董事长兼总经理<span @click="sybox3_dialog2 = true">[详情]</span></div>
                        </div>
                    </div>
                </div>
                <div class="option">
                    <div class="shadow"></div>
                    <div class="label">
                        <div class="icon"> <i class="fas fa-tree"></i> </div>
                        <div class="info">
                            <div class="main">熊立</div>
                            <div class="sub">网龙网络公司CEO<span @click="sybox3_dialog3 = true">[详情]</span></div>
                        </div>
                    </div>
                  </div>
                <div class="option">
                    <div class="shadow"></div>
                    <div class="label">
                        <div class="icon"> <i class="fas fa-tint"></i> </div>
                        <div class="info">
                            <div class="main">林拥军</div>
                            <div class="sub">易华录总经理<span @click="sybox3_dialog4 = true">[详情]</span></div>
                        </div>
                    </div>
                </div>
                <div class="option">
                    <div class="shadow"></div>
                    <div class="label">
                        <div class="icon"> <i class="fas fa-sun"></i> </div>
                        <div class="info">
                            <div class="main">熊群力</div>
                            <div class="sub">中国电子科技集团有限公司董事长、党组书记<span  @click="sybox3_dialog5 = true">[详情]</span></div>
                        </div>
                    </div>
                </div>
                <div class="option">
                    <div class="shadow"></div>
                    <div class="label">
                        <div class="icon"> <i class="fas fa-sun"></i> </div>
                        <div class="info">
                            <div class="main">张桂平</div>
                            <div class="sub">苏宁环球集团董事长<span  @click="sybox3_dialog6 = true">[详情]</span></div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <el-dialog title="践行数字中国梦的领航人--刘欣华" :visible.sync="sybox3_dialog1" width="60%">
          <span>
            <video controls="controls" width="100%">
                <source src="https://flv2.bn.netease.com/videolib3/1802/04/YyHMo0057/SD/YyHMo0057-mobile.mp4" type="video/mp4">
            </video>
            
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sybox3_dialog1 = false">返 回</el-button>
          </span>
        </el-dialog>
        <el-dialog title="陈思华" :visible.sync="sybox3_dialog2" width="60%">
          <span>
            <img src="../../assets/images/sy/sybox3_pic2.jpg" alt="">
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              陈思华说，随着中国数字经济发展进入快车道，大数据正在成为信用数据整合和信用服务的重要方式，并将逐渐渗透到整个行业，打破信息的孤岛，
              最终对分散在不同政府部门、行业组织和社会机构的各类数据进行有效整合。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              “相比传统的信用信息收集方式，大数据信用采集，采用的是云计算服务技术，即从数据录入开始到评价结果的输出，整个过程，全部由计算机算法完成，
              这里面避免了主观判断的影响，可以确保评估评价结果的准确性。”陈思华说，在此基础上，互联网和基于互联网的其它信息技术，
              也为信用服务提供了更高效的途径，即使同时处理多个受评对象，仍然能够保证信用评估的准确高效。“特别是当受评对象的信息发生变化时，
              依托大数据，仍能够对其信用快速及时地计算，保证信用的实时性。”
            </p>
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sybox3_dialog2 = false">返 回</el-button>
          </span>
        </el-dialog>
        <el-dialog title="熊立" :visible.sync="sybox3_dialog3" width="60%">
          <span>
            <img src="../../assets/images/sy/sybox3_pic3.jpg" alt="">
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              在首届数字中国建设峰会上，网龙网络公司与英国培生集团签订战略合作协议。熊立表示，此举希望通过网龙的数字化技术，
              把英国培生这家全球最大的线下教育集团的教育资源逐步线上化。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              “我觉得在教学资源这一块我们是互通的。培生在海外可能拥有更大的教育市场，我们在国内也做了很多教育资源线上和线下的结合。我们和培生的合作，
              就是希望利用传统线下资源的优势和线上资源的优势，把两者相结合起来，能够把整个数字教育的进程推进得更加有效。”熊立进一步解释说。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              此前的4月初，网龙网络公司收购了全球领先学习社区Edmodo。Edmodo平台是全球最大最活跃的学习社区平台之一，拥有超过9，000万注册用户，
              遍布192个国家的400，000所学校，是一个为K-12学校提供面向教师、学生、管理人员和家长的通信和协作平台。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              熊立表示，希望通过这次收购，向打造终身学习平台的目标进发，让网龙的教育产品能够更加全面，至于下一步能否走得更好，还需要付出很大的努力。
            </p><br/>
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sybox3_dialog3 = false">返 回</el-button>
          </span>
        </el-dialog>
        <el-dialog title="林拥军" :visible.sync="sybox3_dialog4" width="60%">
          <span>
            <img src="../../assets/images/sy/sybox3_pic4.jpg" alt="">
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              林拥军介绍，城市数据湖是想给城市构建一个大数据的水利基础设施，利用光存储技术降低全社会数据存储的成本及数据存储的能耗，更有利的发展大数据产业。
              林拥军认为，数据湖建设要分三个阶段，一是建湖搭建大数据仓库，二是引水把社会数据资源引流到湖里，三是数据资源的开发利用。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              “数据湖是大家共同搭建起的基础设施平台，把大量数据存续下来，开放给企业和创业团队，完善城市管理、公共服务，对产业转型升级提供支撑。
              这种模式将极大丰富现在的大数据产业。”他说。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              针对城市数据湖对数字中国建设的意义，林拥军表示，它将起到先导性、基础性支撑作用。“未来每个城市都会有它的数据湖，‘湖’的规模有大有小，
              这将成为城市发展的标配，为区域发展提供综合性数据存储服务。”
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              分析数据湖与云计算之间的关系时，林拥军解释说，很多公有云数据中心，以计算为主，强调计算性能优先，可以称作热数据，热数据从产生两周后，
              访问频率降低就变成冷数据。“现在一个城市中既有数据湖也有云，云是负责处理热数据，湖负责存储冷数据。这样会形成一个冷热的生态。”
              他认为，两者之间不会替代，而是共同构成了生态体系。
            </p><br/>
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sybox3_dialog4 = false">返 回</el-button>
          </span>
        </el-dialog>
        <el-dialog title="熊群力--加快构建新一代信息基础设施 助力数字中国发展" :visible.sync="sybox3_dialog5" width="60%">
          <span>
            <img src="../../assets/images/sy/sybox3_pic5.jpg" alt="">
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              构建全要素感知体系 搭建数字化服务平台
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              传统信息基础设施不包括感知层，近两年中国电科一直在做的一件事就是把对现实世界的万事万物的感知统一起来。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              怎么统一？熊群力认为核心是数据层面的统一，就是把所有的数据用统一的标准、统一的定义、统一的规范整理出来。不管是感知的物体温度、
              运动速度、形态，还是运动过程，都能够用数据群组表现。当数据之间实现处理、融合、交换，数据就变成了一种生产要素。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              熊群力认为，建设新一代信息基础设施，首先各方在理念上、认识上必须更进一步。新一代信息基础设施是在统一的数据标准体系框架内，
              构建全要素的感知体系，打破信息孤岛，搭建基于大数据的服务平台，实现感知、传输、存储、开发和人工智能赋能下的增值应用，
              助力政府提供更具价值的公共服务，为数字中国、智慧社会建设提供数字化、智慧化的信息基础设施和应用支撑。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                在推进示范应用方面，熊群力介绍说，中国电科积极与地方政府和行业部门合作，比如联合上海市在嘉定区开展试点，大力推进“物联、数联、
                智联”三位一体的新型城域物联专网建设，推动城市数字转型和新一轮高质量发展。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              大数据应用前景广阔 开放创新激发数字化活力
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              数据是智慧社会的核心要素，已经融入日常生活，成为生活中的基础性资源。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              “大数据的应用，我们国家走在了世界前列。”熊群力认为，大数据的应用过程虽然漫长，但前景广阔。数据的应用要从行业入手，要对行业本身与经济相关的所有关联数据进行大据分析和处理，
              才能更好地助力政府提供更具价值的公共服务，为智慧社会建设提供数字化、智慧化的信息基础设施。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              熊群力表示，巨大的应用需求是中国大数据应用创新的重要动力。目前，中国在不断探索和创新大数据相关应用，并且在数据利用方面取得一定成绩。他以贵州应用大数据的情况为例说，
              在高速路上用大数据寻找某一个塌方段的伤亡的情况，不管有什么车辆，还是有什么人员，在大数据的支持下很快就可以找到。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              　熊群力表示，中国发展大数据的理念和认识比较超前，提出数字经济的思想具有前瞻性。但具体到大数据技术方面，在数据基本算法、工具方面还存在一定差距。他建议，要通过改革激发科研人员活力，
              通过国际间合作，引进消化吸收新技术，从而推动大数据创新发展，激发数字化社会创新活力。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              加强基础性科学研究 构建新一代信息基础设施
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              电子信息技术与现代科学关系紧密，为国民经济发展做出了重要贡献。尽管在应用领域，中国已经走在前列，但仍需进一步解决关键领域的“卡脖子”问题。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              熊群力认为，中国在电子信息技术的基础研究领域比较薄弱，未来应加大科研创新投入，在基础研究领域实现整体布局、统筹规划。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              具体到中国电科来说，熊群力表示，近些年企业加大了在基础领域的布局，甚至进入到材料、底层科学技术的研究中。此外，中国电科还不断加强系统性布局。“我们虽然是一个集团，但是各个成员单位有各自的科研方向、
              科研内容，我们要加强内部的整合，形成系统，形成体系。”熊群力说，在这一思路的指引下，中国电科给自己定了一个目标，希望到本世纪中叶，成为世界一流的创新型领军企业。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              　加快构建新一代信息基础设施，对增强人民福祉具有积极作用。熊群力说，中国电科未来将继续按照党中央、国务院部署，积极投身新一代信息基础设施的建设进程中。
            </p><br/>
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sybox3_dialog5 = false">返 回</el-button>
          </span>
        </el-dialog>
        <el-dialog title="张桂平--数字经济和新消费成为经济发展新引擎" :visible.sync="sybox3_dialog6" width="60%">
          <span>
            <img src="../../assets/images/sy/sybox3_pic6.jpg" alt="">
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             以下为访谈主要内容： 
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              主持人：您提到大力发展数字经济是目前的提案热点，能不能展开讲一下您对数字经济的看法？
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              张桂平：数字经济是一种新的经济形态，已经渗透到各个经济环节。推动数字经济蓬勃发展，成为经济增长的新动力。当前，我国数字经济发展已经从跟跑、
              并跑向领跑逐步转变，但仍然存在发展不均衡，企业数字化改造面临壁垒较高，数字化转型服务支撑能力不足等问题。因此，我在提案中建议：
              一是要以政府数字转型助推产业数字转型；二是要为数字经济发展提供良好环境；三是要通过创新和服务能力提升，助推服务生态形式升级。我认为，
              能够破除以上几点问题，我国的数字经济一定还能上一个新台阶。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              　主持人：我们注意到您在这次提案中还关注了一个比较新的概念就是新消费的发展，能不能再简单介绍一下？
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              张桂平：如今新消费的模式在实践中层出不穷，逐渐成为经济发展的新引擎，构建全时空的新消费生态圈及其自身体系，对发展新消费至关重要。
              当然，我国新消费领域也还存在一些问题，比如企业对新消费概念的把握不够准确，中华文化元素彰显不明显等。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              　在新消费方面我还有一些建议：第一，要制定相关的规划政策措施，建立跨部门的推进机制，要通过大数据科学指导营销互动。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              第二，要建立新消费服务标准体系，着重提升服务水平，加强引导养老、教育、医疗、健康等重点领域向规范化、标准化发展。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              第三，就是要讲好中国故事，做好资源汇聚，跨界整合，品牌联动，用文化满足人们对生活品质的追求。
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
/* sybox3手风琴效果 start */
.options {
  display: flex;
  flex-direction: row;
  align-items: stretch;
  overflow: hidden;
  min-width: 600px;
  max-width: 900px;
  width: calc(100% - 100px);
  height: 400px;
margin:60px auto;
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
  bottom: 20px;
  left: 20px;
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
  height: 40px;
  transition: 0.5s cubic-bezier(0.05, 0.61, 0.41, 0.95);
}

.options .option .label .icon {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  min-width: 40px;
  max-width: 40px;
  height: 40px;
  border-radius: 100%;
  background-color: white;
  color: var(--defaultBackground);
}

.options .option .label .info {
  display: flex;
  flex-direction: column;
  justify-content: center;
  margin-left: 10px;
  color: white;
  white-space: pre;
}

.options .option .label .info>div {
  position: relative;
  transition: 0.5s cubic-bezier(0.05, 0.61, 0.41, 0.95), opacity 0.5s ease-out;
}

.options .option .label .info .main {
  font-weight: bold;
  font-size: 1.2rem;
}

.options .option .label .info .sub {
  transition-delay: .1s;
}
/* sybox3手风琴效果 end */

</style>