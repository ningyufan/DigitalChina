<template>
    <div class="GX_index">
        <div id="box1">
			<gxBox1/>			
		</div>
        <div id="box2">
			<gxBox2/>
		</div>
        <div id="box3" >
			<gxBox3/>
		</div>
        <div id="box4">
			<gxBox4/>
		</div>
		<div id="box5">
			<gxBox5/>
		</div>
		<div id="box7" class="box7">
			<gxBox6/>
		</div>
        
    </div>
</template>

<script>
import gxBox1 from './gx_box1'
import gxBox2 from './gx_box2'
import gxBox3 from './gx_box3'
import gxBox4 from './gx_box4'
import gxBox5 from './gx_box5'
import gxBox6 from './gx_box6'

export default {
	components:{
		gxBox1,
		gxBox2,
		gxBox3,
		gxBox4,
		gxBox5,
		gxBox6,
	 },
    head:{
        script:[
            {src:'js/jquery.1.7.1.min.js'},
			{src:'js/aos.js'},
        ],
        link: [
            { rel: 'stylesheet', href: 'css/normalize.css' },
            { rel: 'stylesheet', href: 'js/aos.css' },
			{ rel: 'stylesheet', href: 'css/styles.css' },
        ]
    },
    mounted() {
        AOS.init({
            easing: 'ease-in-out',
            duration: 500,
			once :false
        });
	},
    
}
</script>
<style>
</style>