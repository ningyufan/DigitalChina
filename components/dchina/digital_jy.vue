<template>
    <div class="Digital_JY">
        <img class="JY_img wow bounceInDown" data-wow-duration="10s">
        <div class="JY_ct">
            <h3 class="wow bounceInDown">
                共享机遇 共谋发展——数博会加速中国大数据产业融合创新</h3>
            <p class="wow bounceInDown"  data-wow-duration="2s">
                数字经济增添活力。走进贵阳国际会议中心一楼大厅，数博会5周年回顾展通过视听形式，
                吸引了众多参观者驻足欣赏。“这5年来，我们目睹了中国大数据技术日新月异的变化，看
                到了贵州大数据从无到有、从有到逐渐形成集群的过程。”满帮集团CEO张晖感慨地说，作
                为一家在贵州成长起来的大数据企业，每届数博会公司都没有缺席。如今，满帮依托大数
                据提升车货匹配技术，平台认证司机、货主总用户量已经突破810万，业务覆盖全国339个
                城市，年度撮合成交规模达7000亿元。满帮的成长只是中国首个大数据综合试验区贵州大
                力发展数字经济，加快培育高质量发展新动能的一个缩影。“我们大力推动大数据与实体经
                济深度融合，实施‘万企融合’和‘百企引领’大行动，每年建设100个融合标杆项目、1000个
                融合示范项目，计划用3到5年时间，带动1万户以上实体经济企业与大数据深度融合，推动
                传统产业数字化、网络化、智能化转型。”贵州省大数据发展管理局副局长娄松说。
            </p>
            <p class="wow bounceInDown"  data-wow-duration="2s">
                数据互通共享助力精准扶贫：中国一直是世界减贫事业的积极倡导者和有力推动者。2019年
                数博会延续此前对脱贫攻坚领域的关注，首次举办了“大数据与全球减贫”高端对话。</p>
            <p class="wow bounceInDown"  data-wow-duration="2s">
                国际合作“朋友圈”越来越广：纵观每届数博会，参会规模、会议成果等一项项纪录不断被刷新。
                今年，参展企业达到448家，其中境外参展企业达到156家。数博会组委会相关负责人介绍，一
                方面本届数博会加大了境外企业参展优惠支持力度；另一方面，数博会愈发凸显的国际性和专业
                性，也能够为展商提供更好的交流机会、更集中的展示平台、更丰富的行业资源。在科技领域，
                尤其是大数据发展方面，没有开放是不行的。”中国科学院院士梅宏认为，在信息时代要构建人
                类命运共同体，也要构建网络空间命运共同体，在开放中加强联合创新、协同创新，在深化国际
                合作中实现互利共赢。</p>
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
.Digital_JY{
    background-image: url('../../assets/images/dchina/tz_bg.jpg');
    position: relative;
    width: 100%;
    height: 120vh;
    background-size: 100% 120vh;
    box-shadow:#1E90FF 0 0 30px 5px;
}
.JY_img{
    background-image: url('../../assets/images/dchina/jy.jpg');
    float: right;
    width: 30vw;
    height: 40vh;
    background-size: 30vw 40vh;
    
}

.JY_img:hover{
    border: 2px solid white;
    -webkit-transform:scale(1.2);
	-webkit-box-shadow:0px 0px 30px #ccc;
}

.JY_ct{
    font-size: 20px;
    text-indent:2em;
    padding: 10px;
    color:black;
}

</style>
