<template>
    <div class="sy_index">
       <div id="sy_box1" class="sy_box1">
            <syBox1/>
       </div>
        <div class="sy_box2">
            <syBox2/>
        </div>
        <div class="sy_box3">
            <syBox3/>
        </div>
        <div class="sy_box4">
            <syBox4/>
        </div>
        <div class="sy_box5">
            <syBox5/>
        </div>
    </div>
</template>

<script>
import syBox1 from './sy_box1'
import syBox2 from './sy_box2'
import syBox3 from './sy_box3'
import syBox4 from './sy_box4'
import syBox5 from './sy_box5'
export default {
    components: {
        syBox1,
        syBox2,
        syBox3,
        syBox4,
        syBox5,
    },
    head:{
        script:[
            {src:'js/jquery.1.7.1.min.js'},//aos
            {src:'js/aos.js'},//aos
            // {src:'js/index.js'},//box2_style
        ],
        link: [
            { rel: 'stylesheet', href: 'css/normalize.css' },//aos
            { rel: 'stylesheet', href: 'js/aos.css' },//aos
            { rel: 'stylesheet', href: 'css/styles.css' },//aos
            { rel: 'stylesheet', href: 'https://fonts.googleapis.com/css?family=Open+Sans' },//box2_style
            { rel: 'stylesheet', href: 'css/style2.css' },//box2_style
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
@import "@/assets/css/sy/sy.css";

</style>
