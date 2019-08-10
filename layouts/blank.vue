<template>
    <div class="blank">
        <!-- <div id="large-header" class="large-header">
            <canvas id="demo-canvas"></canvas>
        </div>
        <script src='http://www.suneee.com/js/demo-1.js'></script>    -->
        <Header :items = "items"/>
 
        <nuxt />
        <Footer/>
    </div>
</template>

<script>
import Header from '../components/public/header.vue'
import Footer from '../components/public/footer.vue'
export default {
    props:['newId'],
    
    components:{
        Header,
        Footer,
    },
    head:{
        script:[
            {src:'http://www.suneee.com/js/TweenLite.min.js'},
            {src:'http://www.suneee.com/js/EasePack.min.js'},
            {src:'http://www.suneee.com/js/rAF.js'},
        ],
        link: [
		    ],
        
    },
    data(){
       return{
            uid:'',
            items: [{
            id:0,
            title:'大数据和数据中国',
			href:'chinese_index',
			img:'@/assets/images/wuti.png',
			p:'数字中国旨在以遥感卫星图像为主要的技术分析手段，在可持续发展、农业、资源、环境、全球变化、生态系统，水土循环系统等方面管理中国',
			li:[{li_name:'针对性研究',li_href:'#'},
				{li_name:'资源卫星',li_href:'#'},
				{li_name:'提高国产化水平',li_href:'#'},
				{li_name:'经济发展',li_href:'#'},
				{li_name:'更多>>',li_href:'#'}] 
			},{
            id:1,
            title:'数字中国',
			href:'c_DigitalChina',
			img:'@/assets/images/wuti.png',
			p:'数字中国介绍',
			li:[{li_name:'',li_href:''},
				{li_name:'',li_href:''},
				{li_name:'',li_href:''},
				{li_name:'',li_href:''},
				{li_name:'',li_href:''}] 
			},{
            id:0,
            title:'数字广西',
			href:'c_DigitalGX',
			img:'@/assets/images/wuti.png',
			p:'数字广西介绍',
			li:[{li_name:'',li_href:''},
				{li_name:'',li_href:''},
				{li_name:'',li_href:''},
				{li_name:'',li_href:''},
				{li_name:'',li_href:''}] 
			},{
            id:0,
            title:'数字玉林',
			href:'c_DigitalYL',
			img:'@/assets/images/wuti.png',
			p:'数字玉林介绍',
			li:[{li_name:'',li_href:''},
				{li_name:'',li_href:''},
				{li_name:'',li_href:''},
				{li_name:'',li_href:''},
				{li_name:'',li_href:''}] 
			},{
            id:0,
            title:'数字玉师',
			href:'c_DigitalYS',
			img:'@/assets/images/wuti.png',
			p:'数字玉师介绍',
			li:[{li_name:'',li_href:''},
				{li_name:'',li_href:''},
				{li_name:'',li_href:''},
				{li_name:'',li_href:''},
				{li_name:'',li_href:''}] 
			},{
            id:0,
            title:'关于我们',
			href:'aboutMe',
			img:'@/assets/images/wuti.png',
			p:'关于我们介绍',
			li:[{li_name:'',li_href:''},
				{li_name:'',li_href:''},
				{li_name:'',li_href:''},
				{li_name:'',li_href:''},
				{li_name:'',li_href:''}] 
			}]
       }
    }

}
</script>

<style>
.large-header {
	position: absolute;
	width: 100%;
	/* background: rgb(255, 255, 255); */
	overflow: hidden;
	background-size: cover;
	background-position: center center;
	z-index: 1;
}
.blank {
    width: 100vw;
}

</style>
