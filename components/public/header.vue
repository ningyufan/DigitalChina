<template>
<div class="header_one">
    <div class="header " id="header" >
		<div class="logo">
			<a href="#">
				Digital <img src="../../assets/images/logo.png" height="30vh" width="30vw" alt=""> China
			</a>
        </div>
        <div class=" fixed-width clearfix" :class="{fixed: isFixed}">
            <div class="header-title fl" style="text-align: center">
				 <header-nav @li_nav = "nav"/>
			</div>
        </div>
		<div class="doc">
			<template v-if="nav_lock == 0">
				<Carousel :items = "items"/>
			</template>
			<template v-if="nav_lock == 1">
				<mk/>
			</template>
			<template v-if="nav_lock == 2">
				<GxCard/>
			</template>
			<template v-if="nav_lock == 3">
				数字玉林
			</template>
			<template v-if="nav_lock == 4">
				<YSBlock/>
			</template>
			<template v-if="nav_lock == 5">
				关于我们
			</template>
		</div>
		
			
			
			
    </div>
</div>
</template>
 
<script>
import HeaderNav from './nav'
import Carousel from './carousel'
import animated from 'animate.css'
import GxCard from '../GX_card'
import Mk from '../../components/dchina/mk'
import YSBlock from '../YS_Block'
	export default {
		props:['items'],
		components:{
			HeaderNav,
			Carousel,
			Mk,
			GxCard,
			YSBlock,
		},
	  data () {
	    return {
			isFixed: 0,
			nav_lock:0,
	    }
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
	  },
	}
</script>
 
<style scoped lang="scss">
@import "@/assets/css/index/page_index.css";


</style>
