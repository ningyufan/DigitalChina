<template>
    <div class="Digital_YY">
        <img class="YY_img wow bounceInDown" data-wow-duration="10s">
        <div class="YY_ct">
            <h3 class="wow bounceInDown">
                “数字经济”发展隐忧浮现</h3>
            <p class="wow bounceInDown"  data-wow-duration="2s">
                随着大数据在国家治理、经济发展等方面的影响日益加深，数据安全问题逐渐凸显，个人信息泄
                露、网络诈骗给公民人身和财产安全带来威胁。进入“数字经济”时代，如何给数据安全“上锁”成
                为2019中国国际大数据产业博览会与会专家讨论的焦点。
            </p>
            <p class="wow bounceInDown"  data-wow-duration="2s">
                “数字经济”高速发展伴随安全隐忧：如今，大数据全面融入社会经济、健康医疗、衣食住行等方方面面。
                数字经济时代，数据的集聚开发应用加大了个人隐私泄露、泄密的风险。此外，大数据本身也在帮助黑客
                来进行相应的数据分析。继《中华人民共和国网络安全法》颁布实施后，2018年《个人信息保护法》被列
                入五年立法规划，2019年《中华人民共和国数据安全法》被列入年度立法规划。</p>
            <p class="wow bounceInDown"  data-wow-duration="2s">
                加快数据分层分级保护：5月28日，国家网信办发布《数据安全管理办法（征求意见稿）》，就维护国家安
                全、社会公共利益，保护公民、法人和其他组织在网络空间的合法权益，保障个人信息和重要数据安全，征
                求广大网民意见。</p>
            <p class="wow bounceInDown"  data-wow-duration="2s">
                全面提升数据安全保障能力:与会专家指出，应建立管理、技术、运营、监管四个维度，平台、数据、应用三
                个层次的全方位数据安全防护体系。数据安全人才短缺的现象也是与会专家关注的焦点，尤其是如何加快培养
                政企机构急需的安全分析型人才。公安部网络安全保卫局总工程师、贵州大数据及网络安全专家委员会副主任
                郭启全等专家分析，应加快专业技术人才队伍培养，加快培育安全企业。
            </p>
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
.Digital_YY{
    background-image: url('../../assets/images/dchina/tz_bg.jpg');
    position: relative;
    width: 100%;
    height: 120vh;
    background-size: 100% 120vh;
    box-shadow:#1E90FF 0 0 30px 5px;
}
.YY_img{
    background-image: url('../../assets/images/dchina/yy.jpg');
    float: right;
    width: 30vw;
    height: 40vh;
    background-size: 30vw 40vh;
    
}

.YY_img:hover{
    border: 2px solid white;
    -webkit-transform:scale(1.2);
	-webkit-box-shadow:0px 0px 30px #ccc;
}

.YY_ct{
    font-size: 20px;
    text-indent:2em;
    padding: 10px;
    color:black;
}

</style>
