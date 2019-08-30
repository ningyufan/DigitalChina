<template>
    <div class="sy_content8">
        <div class="sycon8_t">
            5G大发声
        </div>
        <div class="sycon8_info">
            <div class="sycon8_infobg">
                <img src="../assets/images/sy/sycon8_bg.png" alt="">
            </div>
            <div class="sycon8_box1" aos = "fade-right" >
                <div class="sycon8_box1_t">5G标准是如何制定的</div>
                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5G标准由诸多技术组成，编码是非常基础的技术，世界各大阵营一度曾就信道编码标准争辩激烈。<span  @click="sycon8_dialog1 = true">[详情]</span></p>
            </div>
            <div class="sycon8_box2" aos = "fade-left" aos-delay = "300">
                <div class="sycon8_box1_t">5G商用年收益将超万亿</div>
                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;2020年，5G首次全面商用即可为我国带来约1.2万亿元的巨大间接收入。<span  @click="sycon8_dialog2 = true">[详情]</span></p>
            </div>
            <div class="sycon8_box3" aos = "fade-right" aos-delay = "600">
                <div class="sycon8_box1_t">毫米波破解5G大难题</div>
                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;标准落地，商用冲刺。然而，在5G一路狂奔的道路上，频谱资源短缺成了一大拦路的难题。<span  @click="sycon8_dialog3 = true">[详情]</span></p>
            </div>
            <div class="sycon8_box4" aos = "fade-left" aos-delay = "900">
                <div class="sycon8_box1_t">2020年5G通信有望商用</div>
                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;在2018世界移动大会上，三大运营商以及产业链上多家企业纷纷发布了最新的5G部署计划。<span  @click="sycon8_dialog4 = true">[详情]</span></p>
            </div>
            <div class="sycon8_box5" aos = "fade-right" aos-delay = "1200">
                <div class="sycon8_box1_t">5G≠4G+1G</div>
                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;5G并不仅仅是简单地在4G上加1G，5G不仅能带来更快的传输速率和更高的网络带宽，也将带来超高可靠性和低延迟。 <span  @click="sycon8_dialog5 = true">[详情]</span></p>
            </div>
            <div class="sycon8_box6" aos = "fade-left" aos-delay = "1500">
                <div class="sycon8_box1_t">这项“黑科技” 或让5G手机提前半年问世</div>
                <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;近日，高通公司推出了全球首款面向智能手机和其他移动终端的全集成5G新空口（5G NR）毫米波及6GHz以下射频模组。 <span  @click="sycon8_dialog6 = true">[详情]</span></p>
            </div>
        </div>

        <el-dialog title="5G标准是如何制定的" :visible.sync="sycon8_dialog1" width="60%">
          <span>
               <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                5G标准由诸多技术组成，编码是非常基础的技术。在5G相关标准中，世界各大阵营一度曾就信道编码标准争辩激烈。2016年，
                中国通信企业力推的Polar成为控制信道编码。这是中国在信道编码领域首次突破，为中国在5G标准中争取较以往更多的话语权奠定了基础。
                “从这个角度看，中国在一定程度上可以说已跻身世界前列”。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                5月21日至25日，国际移动通信标准化组织3GPP工作组在韩国釜山召开了5G第一阶段标准制定的最后一场会议。据悉，
                本次会议将确定3GPP R15标准的全部内容，预计下月在美国召开的全体会议上，3GPP将宣布5G第一阶段的确定标准。
                那么，负责电信标准制定的3GPP是一个怎样的组织？广受关注的5G标准是如何制定的？中国企业在5G标准制定过程中拥有多大的话语权？
                带着这些问题，北京青年报记者对业内人士进行了采访。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;                
                <b>5G独立组网标准有望下月发布确立 </b>
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                在这次3GPP釜山会议上，所有开发5G无线技术的工作组将在这次会议上汇总，最终确定5G RAN商业化的相关标准技术。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                在会议上将有来自芯片组、手机和设备供应商、移动运营商等约1500名标准专家参加会议，以完成5G第一阶段的标准。
                其中包括提供超高速数据和超低时延的5G无线接入技术以及用于5G终端的一致性测试方法。简单来说，此次釜山会议结束后，
                5G第一阶段中独立组网标准已出炉在即。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                多家中国企业包括华为、OPPO、VIVO等通信设备及手机厂商，也参会商讨并提交了提案。华为5G产品线总裁杨超斌表示，按计划，
                这次会议将完成有关5G独立组网(SA)的标准技术，审议通过后将在下月美国全会上正式宣布，华为也准备了提案。此次标准确定后，
                设备企业有基于标准的设备就可以商用。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                此前3GPP确定5G标准化分为两个阶段：第一阶段启动R15为5G标准，于2018年6月完成；第二阶段启动R16为5G标准，于2019年12月完成。
                下月在美国举行的3GPP会议上将最终确定5G第一阶段标准。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                <b>5G标准到底有几个?</b>
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                有读者不免疑惑，去年的时候不是说3GPP已经确定了一个5G标准吗？怎么现在又确定一次？为什么还有说法称，最终的标准要等到2019年，甚至2020年？
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                “上一次确定的是非独立组网标准，这一次将确定的是5G独立组网标准。”资深通信观察家项立刚接受采访时指出，非独立组网，简单来说，就是不是独立组成的5G网络，
                要和其它东西融合，比如与4G甚至3G共同组网；而5G独立组网，则意味着是完全没有4G，完整建立的5G网络。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                “在非独立组网中，5G拿来干吗？5G拿来作为补充，大的网络是4G，但是在一些热点地区，比如奥运会赛场、CBD等等，这些局部区域通过5G增加热点来提升网络速度和用户感知、体验，
                但整个大范围的网络仍不是用5G。相比之下，5G独立组网，是指整个网络完全用5G形成覆盖。”项立刚进一步解释说。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                　“独立组网标准的制定，意味着5G整个网络的部署标准已趋向完善”，项立刚表示，非独立组网以热点为核心，解决的是小范围的局部性的热点覆盖问题；现在独立组网标准之下，
                5G全面网络覆盖问题都可以解决，因此说此次标准的确立非常重要，可以认为5G标准更进一步，更加完善了。
            </p><br/>
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sycon8_dialog1 = false">返 回</el-button>
          </span>
        </el-dialog>

        <el-dialog title="5G商用年收益将超万亿" :visible.sync="sycon8_dialog2" width="60%">
          <span>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              2020年，5G首次全面商用即可为我国带来约1.2万亿元的巨大间接收入。记者昨天获悉，手机5G套餐包含的流量有望十倍于现在，并将让有线宽带与WiFi“退休”。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
              在世界移动互联网大会上，中国移动研究院副院长黄宇红披露，我国物联网已有3.8亿以上的连接，5G会带来一个极其广阔的市场。测算显示，除了运营商收入，5G在2020年首次全面商用即可实现1.2万亿元的间接收入，2021年就能达到2.3万亿元，2022年将升至4万亿元左右。对于未来数字经济的发展，5G将成为一个重要基础。黄宇红介绍，中国移动不仅成立了5G联合创新中心，
              还在全国建设了14个开放实验室，并准备发起成立5G创业基金，来支持5G的创新和创业。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
               中国电信综合平台公众流量事业部总经理李宇光在会上更是大胆预测，随着5G网络的铺开，其高速度和高带宽的优势，将直接打压有线宽带和WiFi的使用量。在5G时代，预计有线宽带的地盘将逐渐缩小，直至消失。
            </p><br/>
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sycon8_dialog2 = false">返 回</el-button>
          </span>
        </el-dialog>

        <el-dialog title="毫米波破解5G大难题" :visible.sync="sycon8_dialog3" width="60%">
          <span>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             标准落地，商用冲刺。然而，在5G一路狂奔的道路上，频谱资源短缺成了一大拦路的难题。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             相较于以往任何一代通信系统，5G需要满足更加多样化的场景和极致性能挑战，那么就需对支持5G新标准的候选频段进行全频段布局，然而，低频段已经异常拥挤，且大多涉及与其他系统干扰保护。在全球大多数地区，目前最直接的方式是利用频率较高的频段，
             包括6GHz以下的3GHz左右频段及24GHz以上毫米波频段，与低频相比，这些频段拥有更多可用带宽。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             在寻找新的频谱资源的过程中，我国也面临着前所未有的频谱资源短缺困境。4G之前就已经逐渐消耗了低频段中的优质频率，于是我国率先为5G划分了低频频段，依照规划，我国对5G频段资源主要集中在3.5GHz和4.8GHz频段。
             而之前备受关注，却一直停留在征求建议阶段的毫米波也有望取得进展。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             在不久前结束的5G和未来网络战略研讨会上，工信部通信发展司副司长陈立东要求，加强移动通信空口技术演进、毫米波等新技术领域的研究。未来移动通信技术和标准发展推进委员会专门设立的5G微波毫米波技术特别工作组，
             发布了5G毫米波频谱规划建议白皮书，呼吁我国迫切需要明确5G在毫米波频谱布局并尽早确立可用频段，应尽早规划24.75~27.5GHz以及37~42.5GHz，给产业明确指导方向，建议2018年年底完成频率规划，支撑2019年毫米波预商用试验以及2020年毫米波大规模商业部署。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             其实，在我国，毫米波技术也并不是一项此前从未涉及的技术。对此，对上述白皮书有着重要内容贡献的美国高通公司有着深刻的体验。该公司中国区研发负责人徐表示，通过与众多中国厂商、合作伙伴的交流发现，
             中国在毫米波技术上的积累并不薄弱，许多研究机构和大学都有相关的研究积累，在基站技术中也有一定程度的应用。“实际上毫米波技术已在很多领域得以应用了，而我们现在需要推动此技术走向更为广泛的商业应用。”
             记者了解到，在技术支持层面，包括多天线技术、宽带的自动处理能力等，我国已经有了一定的技术储备作为毫米波技术的基础，可能先利用6GHz以下频段技术。目前，很多中国运营商和厂商在积极推动毫米波技术在这一频段的应用。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             放眼全球，对毫米波进行规划已是大势所趋。目前，在6GHz以下频段，我们看到3GHz左右的频段在全球都获得关注。全球许多国家正在划分或计划划分24GHz以上的毫米波频段。2016年7月，美国将多达11GHz的毫米波频谱划分为5G频段。
             包括欧洲、韩国、日本、澳大利亚和加拿大在内的其他地区也正在划分用于5G的毫米波频谱。在某些情况下，其中一部分的毫米波频谱可能会被划分为共享或非授权频谱——而不是授权频谱，这在特定情况下可能是必需的。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             “毫无疑问，毫米波频谱在中国和全球范围内对于5G都至关重要。毫米波频段可提供极致带宽，因此其对于满足更好、更快的增强型移动宽带需求至关重要，同时与目前中国和世界其他地区的千兆级LTE服务相比，
             毫米波频段可为5G提供显著的差异化。”徐这样认为。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             这种重要性在一系列测试中的对比数据上可见一斑。对此，高通进行了一系列5G真实网络模拟实验。在美国旧金山的实验中进行了5G网络模拟实验，通过现有的LTE的基站辅以毫米波容量，实现了5倍的网络容量增益，同时，在4G达到100%覆盖的情况下，
             将毫米波加入现有的4G基站，可以实现5G网络65%的覆盖率。在法兰克福的另一组实验则是在6GHz以下频谱上进行的4G转换为5G的模拟实验，就下载速率而言，从4G用户均值的56Mbps提升至5G用户均值的超过490Mbps，实现了8.8倍的增益，从小区边缘突发数据而言，可以达到9.2倍的增益。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             得益于试验的成果，目前，高通已经开发并展示利用6GHz以下和毫米波这两个频段范围的试验平台，并推出可支持在6GHz以下和毫米波频段运行的5G新空口的调制解调器骁龙X50。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             对于毫米波的挑战，徐也坦言：“使用毫米波频段传输更容易造成路径受阻与信号衰减，因此，毫米波信号传输的高效性和鲁棒性是我们的研发重点之一，另外，对于如何使毫米波技术更好地适应终端的尺寸和功耗也是高通的技术研究方向。”（那什）
            </p><br/>
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sycon8_dialog3 = false">返 回</el-button>
          </span>
        </el-dialog>

        <el-dialog title="2020年5G通信有望商用" :visible.sync="sycon8_dialog4" width="60%">
          <span>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             在日前举行的2018世界移动大会上，我国移动通讯领域三大运营商以及产业链上多家企业纷纷发布了最新的5G部署计划，明确在2020年实现5G正式商用。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             按照工业和信息化部规划，我国5G试验将分两步走：第一步是2016年到2018年底，为5G技术研发试验，主要目标是参与支撑5G国际标准制定；第二步是2018年到2020年底，为5G产品研发试验，主要目标是开展5G预商用测试。按照这一时间表，业界一致认为，
             我国有望在2019年实现5G通信预商用，2020年实现5G通信大规模正式商用。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             中国联合网络通信集团有限公司总经理陆益民表示，在5G领域，中国联通已经在16个城市陆续开启了5G规模试验，2019年将进行业务应用示范及试商用，并计划在2020年正式商用。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             中国移动通信集团有限公司董事长尚冰说，中国移动将大力推进5G规模试验和应用示范，争取在2018年进行规模试验，2019年实现预商用，2020年实现全面商用。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             为了实现2020年5G正式商用的目标，整个产业链的商用步伐都在加速。尤其是5G独立组网标准日前刚刚冻结，意味着5G第一阶段全功能标准化工作已经完成并发布，进入了产业全面冲刺阶段。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             中国联通表示，其5G网络将以独立组网标准为目标架构，前期聚焦增强移动宽带，持续保持中国联通在3G和4G时代的网络速率优势，为高清视频、虚拟现实/增强现实游戏娱乐、车载影音、智能家庭等大流量高带宽应用提供全方位的网络支持。
             后续将结合技术标准和生态系统的发展进程，积极引入低时延、高可靠和海量机器类通信技术，提供车联网、工业互联网等垂直行业的数字化转型支持。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             在2018世界移动大会期间，中国移动联合大唐电信、爱立信、华为、英特尔和诺基亚等全球合作伙伴共同发布“5G SA（独立组网）启航行动”，目的正是促进独立组网从标准走向真正商用化，推动端到端产品尽快成熟。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             大会期间，中央网信办副主任杨小伟和上海移动技术人员进行了全球首个5G独立组网端到端系统全息视频通话，通话首次采用5G独立组网端到端系统技术，标志着5G独立组网技术取得突破进展，5G产业发展正全力加速。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             此前，中国移动还对外发布了12项5G创新成果。中国移动通信集团有限公司副总裁李正茂向江苏、湖北、贵州3个开放实验室正式授牌。目前，中国移动5G联合创新中心已拥有224家产业合作伙伴，在美国、
             瑞典和中国共建立了14个开放实验室，联合合作伙伴开展了数十个5G创新项目。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             尚冰表示，中国移动要以独立组网为目标架构规划5G网络，推进5G网络部署云化，加速推进5G产业端到端成熟，依托5G联合创新中心以及5G产业研究院，开展智慧城市、车联网、工业互联网等创新平台和研发应用。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             中国电信在2018世界移动大会前一天发布了《中国电信5G技术白皮书》，这是全球运营商首次发布全面阐述5G技术观点和总体策略的白皮书。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             中国电信集团有限公司总经理刘爱力表示，中国电信将从技术创新和产业合作两个方面全力推动5G发展。在技术创新方面，截至2018年6月底，中国电信共主导5G国际标准项目及任务31项，提交国际文稿457篇；
             申请技术专利190项，其中143项获得专利保护。在产业合作方面，中国电信首批启动了雄安等六城市的5G创新示范网建设，并于2017年12月开通全部5G试点基站；2018年2月，
             国家发展改革委正式批复中国电信在北京等12个城市开展5G规模建设及应用示范工程。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             中国移动在大会期间发布的《5G终端产品指引》显示，要在2018年底推出首批5G芯片，在2019年第一季度推出首批5G终端，在2019年第三季度推出5G智能手机。中国移动还与28家“5G终端先行者计划”成员，
             包括6家主流芯片企业、13家主流终端企业、5家元器件企业、4家仪表企业签署了合作备忘录，以加快5G终端产业发展和孵化产品。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             　显然，按照这一进度表，终端厂商也要加快速度。华为公司轮值董事长徐直军表示，华为将于2019年3月30日推出基于独立组网标准的5G商用系统，在2019年推出支持5G的麒麟芯片，并将于2019年6月推出支持5G的智能手机。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             高通公司总裁克里斯蒂安诺·阿蒙也表示，5G数据终端将于今年12月份在部分市场发布，而与高通合作的代工厂商将在明年三四月份就能推出首批具备完整5G功能的智能手机。
            </p><br/>
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sycon8_dialog4 = false">返 回</el-button>
          </span>
        </el-dialog>

        <el-dialog title="5G≠4G+1G" :visible.sync="sycon8_dialog5" width="60%">
          <span>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             万物互联，海量的数据需要强大稳定的网络来支持，作为新一代通信技术，5G正向我们走来。5G的商用将推进哪些领域的发展？
             日前在英特尔（中国）举行的“加速通向5G之路”行业沙龙上，学界和业界专家给出了解答。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             英特尔(中国）通信与设备事业部无线标准首席技术专家吴耕说，5G并不仅仅是简单地在4G上加1G，5G不仅能带来更快的传输速率和更高的网络带宽，也将带来超高可靠性和低延迟。
             未来，无人驾驶、虚拟现实、智慧城市等领域将因5G而释放巨大的潜力。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             “5G时代，人和人、人和物、物和物都将连成一体，将构建一个全新的信息化的基础设施。”中国信息通信研究院信息化与工业化融合研究所副所长许志远说。他说，当前一些应用，
             比如无人驾驶汽车需要的高可靠性、低时延，4G没法满足，5G的出现将给无人驾驶带来良好的用户体验。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             吴耕介绍，5G能够实现延迟低于1毫秒，峰值传输速率高达10G bps（比特每秒）。超低延迟和大数据文件的高速传输让5G能够像第六感一样近乎实时地获取与周围环境的信息。
             汽车可使用基于云的人工智能和数据，与路上其他汽车以及包括路灯在内的交通基础设施进行实时“沟通”。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             虚拟现实将改变人们认知现实的方式。许志远说，从计算到传感，特别是在通信上，虚拟现实目前还没有做到给用户提供良好体验的准备，5G将大大改进虚拟现实的体验，
             并让无处不在的实时视频分享、随时随地云接入等都将成为现实。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             全球统一的标准能为未来5G的发展打好坚实的基础。在全球统一的标准下,无论中国还是欧洲的智能设备都能正常接通，不仅能降低成本，还能给用户带来极大便利。
             由于以往的2G、3G、4G系统主要服务于通信，所以存在多制式标准并行的情况。工信部第五代移动通信技术推进组专家罗振东表示，进入5G时代后，市场将迎来一个“真正意义上的融合网络”。
             包括中国在内，世界各国都努力在全球范围内实现5G标准化。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             我国已经全面启动5G技术研发试验，中国5G试验也是全球首个由政府主导和规划的国家5G试验。今年美国通信运营商Verizon宣布将在美国11座城市进行5G试验性运营；中国5G网络第二阶段测试也计划于今年正式开启。
             业界普遍预计，标准化的5G网络预计将于2020年前后实现商用。
            </p><br/>            
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sycon8_dialog5 = false">返 回</el-button>
          </span>
        </el-dialog>

        <el-dialog title="这项“黑科技” 或让5G手机提前半年问世" :visible.sync="sycon8_dialog6" width="60%">
          <span>
            <img src="../assets/images/sy/sycon8_pic1.jpg" alt="">
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             近日，高通公司推出了全球首款面向智能手机和其他移动终端的全集成5G新空口（5G NR）毫米波及6GHz以下射频模组。这两个分别支持毫米波和6GHz以下的射频模组，
             可适应不同区域不同运营商的不同频段。业内人士认为，这项关于5G手机关键“黑科技”的研发成功，将至少让手机厂商提前半年推出5G手机，加速全球5G商用。
            </p><br/>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
             这款毫米波5G射频模组可与骁龙X50 5G调制解调器协同工作并形成完整系统，以应对毫米波带来的巨大挑战。作为完整系统，其可支持先进的波束成形、波束导向和波束追踪技术，
             显著改善毫米波信号的覆盖范围及可靠性。更重要的是，高通推出的这款5G射频模组尺寸精致小巧，可谓指尖上的模组。手机厂商可以很容易把它集成到手机中，
             这样制造出来的手机就能尽量保持外观、厚度都与4G手机接近。（通讯员刁兴玲 记者李丽云）
            </p><br/>
          </span>
          <span slot="footer" class="dialog-footer">
            <el-button type="primary" @click="sycon8_dialog6 = false">返 回</el-button>
          </span>
        </el-dialog>
    </div>
</template>

<script>
export default {
    layout: 'content2',
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