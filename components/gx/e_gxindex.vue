<template>
    <div class="GX_index">
        <div id="box1">
			<egxBox1/>			
		</div>
        <div id="box2">
			<egxBox2/>
		</div>
        <div id="box3" >
			<egxBox3/>
		</div>
        <div id="box4">
			<egxBox4/>
		</div>
		<div id="box5">
			<egxBox5/>
		</div>
		<div id="box6">
			<egxBox6/>
		</div>
        
    </div>
</template>

<script>
import egxBox1 from './e_gx_box1'
import egxBox2 from './e_gx_box2'
import egxBox3 from './e_gx_box3'
import egxBox4 from './e_gx_box4'
import egxBox5 from './e_gx_box5'
import egxBox6 from './e_gx_box6'

export default {
	components:{
		egxBox1,
		egxBox2,
		egxBox3,
		egxBox4,
		egxBox5,
		egxBox6,
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