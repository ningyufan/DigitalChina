<template>
    <div class="blank">
        <div id="large-header" class="large-header">
            <canvas id="demo-canvas"></canvas>
        </div>
        <script src='http://www.suneee.com/js/demo-1.js'></script>
        <el-container>
            <el-header>
                <Header/>
            </el-header>
            <el-main>
                <nuxt />
            </el-main>
            <el-footer>
                <Footer/>
            </el-footer>
        </el-container>
    </div>
</template>

<script>
import Header from '../components/public/header.vue'
import Footer from '../components/public/footer.vue'
export default {
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
.el-container{
    min-height: 100vh;
    z-index: 2;
}
.el-header,.el-main,.el-footer{
    width: 1190px;
    margin: 0 auto;
    padding: 0;
    overflow: unset;
    z-index: 2;
}
.el-main{
    background: rgb(240, 235, 235);
    z-index: 2;
}
.el-header{
    z-index: 3;
    min-height: 60px;
}

</style>
