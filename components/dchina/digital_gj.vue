<template>
    <div class="Digital_GJ">
        <img class="GJ_img wow bounceInDown" data-wow-duration="10s">
        <div class="GJ_ct">
            <h3 class="wow bounceInDown">
                大数据成为提高财政收入有力工具</h3>
            <p class="wow bounceInDown"  data-wow-duration="2s">
                开拓创新型大数据交易体系:贵州省政协副主席、秘书长任湘生在致辞时，回顾并展望了贵州
                大数据产业发展的情况，对大数据交易产业发展寄予厚望。任湘生说，期望大数据交易发挥好
                汇聚数据资源、融合数据资源的重要作用，尽力打好前哨，推动大数据应用不断拓展。同时，
                制定大数据交易关键共性标准，不断完善大数据交易体制机制建设，在坚守数据安全底线的基
                础上，打造大数据交易生态，创建产学研用积极互动的良好格局，开拓发展创新型大数据交易
                体系。
            </p>
            <p class="wow bounceInDown"  data-wow-duration="2s">
                重新构建大数据版图：清华大学新闻与传播学院院长、原国家新闻出版总署署长柳斌杰，就“打
                通数字鸿沟，开发数据资源”发表主题演讲。柳斌杰表示，发展大数据产业要深度挖掘人类创造
                的数据资源宝库，不仅要高速收集已经数字化了的各种流动、交易的数据，还要激活沉睡在各个
                角落的数据，让所有的数据活起来，重新构建大数据版图，真正做到数据共享。发展大数据是推
                进智能化建设的必经之途，大数据是人工智能的基石。</p>
            <p class="wow bounceInDown"  data-wow-duration="2s">
                大数据对绿色发展具有重要促进作用：清华大学中国经济社会数据研究中心主任、国家统计局原
                副局长许宪春发表了题为《大数据与绿色发展》的主题演讲。许宪春认为，实现我国绿色发展的
                关键途径在于加快产业结构转型升级，加快新经济发展，而大数据在其中发挥的作用不容小觑。
                研究大数据对绿色发展的具体影响，有利于推动绿色发展取得实质性进展。他表示，大数据在资
                源整合、科学决策、平台建设、环境监管等方面，可以为绿色生产、绿色生活、美好环境提供重
                要的手段和保障。第一，通过大数据整合资源，促进产业转型升级，实现提质增效；第二，大数
                据通过建立公共服务平台和数据库推动绿色发展；第三，通过大数据保护生态环境，建设环境监
                管体系，将促进绿色发展。“当前，传统的经济增长方式不能再继续，大数据对绿色发展具有显
                著的正外部性，大数据的开发利用对绿色发展具有重要的促进作用。”许宪春说。</p>
            <p class="wow bounceInDown"  data-wow-duration="2s">
                五大策略应对新形势下数据安全挑战：首先，从全球视野看待数据安全问题，只有立足开放环境，
                加强对外交流、合作、互动、博弈，吸收先进技术，网络安全水平才会不断提高。其次，对重要行
                业和领域，以及可能严重危害国家安全、国计民生、公共利益的关键信息基础设施，在网络安全等
                级保护制度的基础上，实行重点保护。再次，新技术已经成为数据安全防护的重要途径。利用大数
                据和人工智能进行态势感知，进行风险识别、研判和预警，解决信息安全问题。第四，依靠法规标
                准解决数据安全问题，加快关键信息基础设施识别、保护框架和实施要求等方面的法律法规、技术
                标准和规范。最后，加强数据保护与使用，制定出台个人信息保护相关法律配套的制度文件和标准
                规范，通过管理制度设计和技术防护措施保障数据不被篡改、不毁坏、不丢失。</p>
            <p class="wow bounceInDown"  data-wow-duration="2s">
                数据财政替代土地财政成为一种趋势：近20年来，政府通过盘活土地资源，实现了经济高速发展，
                城市现代化进程得以加快。然而，随着时代的发展，当前土地财政明显已经难以为继，大数据的出
                现为新时期发展注明了新的内涵与外延，为国际竞争、地区转型、技术创新、经济发展及社会治理
                开辟了新路径。“盘活政府数据资源，建设数据财政架构的时机已经悄然到来。”王叁寿说。王叁寿
                认为，目前我国数据资源80%以上掌握在政府手中。无论是从数据资源分布特点，还是从数据资源
                质量来讲，政府数据是现阶段数量最庞大、价值密度最高、涉足广度最宽的数据资源，涉及工商、
                税务、司法、交通、医疗、教育、通信、金融、地理、气象、房产、保险、农业等众多领域。财政
                收入增长的新逻辑，在于激活数据、融通数据、变现数据，运用好大数据工具是实现这一目标的最
                佳途径。“用增量改革促存量调整，激活政府数据价值是最大的供给侧结构性改革。”王叁寿如此判断。</p>
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
.Digital_GJ{
    background-image: url('../../assets/images/dchina/tz_bg.jpg');
    position: relative;
    width: 100%;
    height: 120vh;
    background-size: 100% 120vh;
    box-shadow:#1E90FF 0 0 30px 5px;
}
.GJ_img{
    background-image: url('../../assets/images/dchina/gj.jpg');
    float: right;
    width: 30vw;
    height: 40vh;
    background-size: 30vw 40vh;
    
}

.GJ_img:hover{
    border: 2px solid white;
    -webkit-transform:scale(1.2);
	-webkit-box-shadow:0px 0px 30px #ccc;
}

.GJ_ct{
    font-size: 14px;
    text-indent:2em;
    padding: 10px;
    color:black;
}

</style>
