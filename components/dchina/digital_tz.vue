<template>
    <div class="Digital_TZ">
        <img class="TZ_img wow bounceInDown" data-wow-duration="5s">
        <div class="TZ_ct">
            <h3>“数字社会”运行状态的四个特征</h3>
            <p class="wow bounceInDown" data-wow-duration="3s">数字化、网络化、大数据、人工智能等当代信息科技的快速发展和广泛应用，
            孕育了“数字社会”这一特定的技术与社会建构及社会文化形态。数字技术进步和数字社会发展，
            成为当代人类社会变迁发展的一大重要特征，这一过程的展开有其内在必然性，是不可逆转的。
            助推“数字社会”快速发展的数字化、网络化、智能化等诸多动力因素使它显现出不同于既往实体社
            会的架构和运行状态。“数字社会”这一特定指称，是“网络社会”或“虚拟社会”一种更为形象化的表达。
            “数字社会”在其基本架构和整体运行上最为突出的一个特点就是它在数字化转换的前提下，依托互联网络，
            从最具有基础性意义的技术保障和运作机制层面，解决人们在社会生活中所必须要面对的一系列基本问题，
            得益于数字化、网络化和智能化的助推，建构起了活动平台和通行路径。“数字社会”和网络生活在运行状态上，
            显现出以下四个方面的本质特征。
            </p>
            <p class="wow bounceInDown" data-wow-duration="3s">第一、跨域连接与全时共在。跨域连接首先解决的是普遍连接的问题。
                普遍连接既包括人与人之间的数字化连接，也包括智能设备与智能设备等物与物之间的数字化连接，
                还包括依托数字化而实现的人、物、智能设备相互之间的连接和贯通。与此同时，跨域连接进一步在
                普遍连接的基础上，依托数字化所带来的虚拟化的独有便利，革命性地解决了跨越地域空间限制而实现
                有效连接的问题，从而真正实现了全球网络一体化的互联互通目标。</p>
            <p class="wow bounceInDown" data-wow-duration="3s">第二、行动自主与深入互动。数字社会、网络时代和赛博空间，客观上为作为社会生活之行为主体的人的行为活动自由，提供了极为便利的基础条件。</p>
            <p class="wow bounceInDown" data-wow-duration="3s">第三、数据共享与资源整合。网络世界贯通的是一个个的人、一台台的电脑和移动终端设备以及一个个的大型服务器和数据库。在某种意义上讲，
                网络空间，其实就是一个信息数据不断生成、存储、流转和分享的特定空间。信息数据的流通和共享，是其独有的优势所在。</p>
            <p class="wow bounceInDown" data-wow-duration="3s">第四、智能操控与高效协作。机械化、自动化和智能化的实现，是科学技术进步带给人类社会生活的“福利”。从根本上来讲，
                人工智能就是基于数字化发展的时代背景，将数据信息获取、数据运算处理和数据挖掘运用紧密结合起来，
                再依托特定设备而得以实现的“类人脑”运算处理和功能呈现过程。</p>
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
.Digital_TZ{
    background-image: url('../../assets/images/dchina/tz_bg.jpg');
    position: relative;
    width: 100%;
    height: 120vh;
    background-size: 100% 120vh;
    box-shadow:#1E90FF 0 0 30px 5px;
}
.TZ_img{
    background-image: url('../../assets/images/dchina/tz.jpg');
    float: left;
    width: 30vw;
    height: 40vh;
    background-size: 30vw 40vh;
}

.TZ_img:hover{
    border: 2px solid white;
    -webkit-transform:scale(1.2);
	-webkit-box-shadow:0px 0px 30px #ccc;
}

.TZ_ct{
    font-size: 20px;
    text-indent:2em;
    padding: 10px;
    color:black;
}

</style>
