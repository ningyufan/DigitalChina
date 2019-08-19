<template>
    <div class="Digital_SD">
        <img class="SD_img wow bounceInDown" data-wow-duration="10s">
        <div class="SD_ct">
            <h3>山东省推进工业互联网发展的思考</h3>
            <p class="wow bounceInDown"  data-wow-duration="2s">山东省提出要大力推进制造业数字化、网络化、智能化作为加快向制造强省迈进的核心驱动力，
                而新一代信息技术与制造业融合的工业互联网在其中发挥着重要作用。围绕工业互联网的发展，
                山东省已经出台系列政策举措，也取得了较为显著的成效。但随着该项工作推进的不断深入，
                需要在科技创新、应用推广以及实施主体及模式等方面进一步明确几个关键问题，制定系统可行的方案，
                从而保证该项工作的顺利开展。工业互联网作为新一代信息技术与制造业深度融合的产物，其通过智能机
                器间的连接并最终将人机连接，结合软件和大数据分析，重构全球工业、激发生产力，大幅提升制造效率。
                因此，在当前全球经济换挡关键期，工业互联网被认为是推动高质量发展的新动能之一，并受到各国广泛推崇。
            </p>
            <p class="wow bounceInDown"  data-wow-duration="2s">但是，随着工业互联网研发及应用的不断深入，当前已没有成熟的经验可借鉴，
                各方参与者都进入自主探索阶段。山东省虽然在前期积累了一定的经验，但推进工业互联网是一项长期而艰巨的任务，需要在未来的
                工作中切实处理好一些关键性、基础性问题，才能支撑其发挥更大作用。</p>
            <p class="wow bounceInDown"  data-wow-duration="2s">首先要明确科技创新的方向。根据工业互联网关键环节，可将创新主要节点大致
                划分为云服务与平台、数据采集、网络安全三个部分。其中，云服务与平台是当前最热门的，比如，“中国工业互联网50佳”中平台类30家、
                网络类8家、工业解决方案类22家、行业应用类2家，而数据服务类为9家，网络安全类仅2家。根据中国工业互联网产业联盟（AII）发布的
                统计结果显示，当前有269个平台类产品。这可能与我国要“到2020年，培育10家左右的跨行业跨领域工业互联网平台和一批面向特定行业、
                特定区域的企业级工业互联网平台”这一规划目标有关。</p>
            <p class="wow bounceInDown"  data-wow-duration="2s">其次应明确推广应用方式。目前工业互联网处于大力推广应用方面，政府及各大平台都
                在极力推动广大企业用户参与进来，也即让其“上云”。其理论依据即GE的1%理论：工业互联网只要提升1%的制造能力就能为整个制造业带来
                上万亿的利润。但另一方面，企业要具体去实施落地的话可能会产生2%的成本（系统部署的全生命周期成本）和3%的风险（系统建设和磨合
                期对企业生产效率的降低，系统应用对企业管理、人事、组织结构等可能造成的负面影响）。因此实际落地来看，微观层面的的单个企业
                （特别是中小企业）对于工业互联网和物联网的热情并不高。</p>
            <p class="wow bounceInDown">三是要明确实施主体及模式。工业互联网与消费互联网有着本质的区别。消费互联网是入口经济、流量经济，
                而工业互联网需要立足于工业，立足于不同的行业，不同行业，千差万别，管理模式、企业基础、行业知识都差异极大，甚至完全不同。
                另外，工业设备之间的协调与对话，也至少需要数千种不同的协议。因此，工业互联网在专业性与通用性方面，存在天然的矛盾。
                一个平台很难既能满足很多不同行业，又对每个用户具有很强的专业性。工信部原副部长杨学山教授对工业互联网的本质有着精
                辟的见解：“工业互联网姓‘工业’，不姓‘互联网’”，“也就是说，工业互联网的使命是为了工业发展的现代化，是为了制造业由
                大变强，为了中国工业真正走上高质量发展之路。这个过程当中使用互联网和带动互联网发展是副产品，不是主题，主题是工业
                的发展。这是至关重要的认识。”</p>
            <center style="margin:3vh auto" class="wow bounceInDown" data-wow-duration="3s">
            <span>来源：学习强国</span>
            </center>
        </div>
    </div>
</template>

<script >
import animated from 'animate.css' 
export default {
    methods: {
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
 
	  	}
	  },
    mounted() {
    this.$nextTick(() => {
        this.handleAnimate()//初始化第一次加载时在视口内就执行动画
        addEventListener('scroll', this.handleScroll);
        addEventListener('scroll', this.handleAnimate);

    })
    
    },
    destroyed() {
        removeEventListener('scroll', this.handleScroll);//避免影响其他页面
        removeEventListener('scroll', this.handleAnimate);
    }


}
</script>

<style>
.Digital_SD{
    background-image: url('../../assets/images/dchina/tz_bg.jpg');
    position: relative;
    width: 100%;
    height: 120vh;
    background-size: 100% 120vh;
    box-shadow:#1E90FF 0 0 30px 5px;
}
.SD_img{
    background-image: url('../../assets/images/dchina/sd.jpg');
    float: right;
    width: 30vw;
    height: 40vh;
    background-size: 30vw 40vh;
}

.SD_img:hover{
    border: 2px solid white;
    -webkit-transform:scale(1.2);
	-webkit-box-shadow:0px 0px 30px #ccc;
}

.SD_ct{
    font-size: 17px;
    text-indent:2em;
    padding: 10px;
    color:black;
}

</style>
