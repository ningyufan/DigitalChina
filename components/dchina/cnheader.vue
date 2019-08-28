<template>
    <div class="cn_header">    
        <el-carousel :interval="5000" arrow="never" height="55vh">
            <el-carousel-item v-for="item in 5" :key="item">
            <h3>{{ item }}</h3>
            </el-carousel-item>
        </el-carousel>
    </div>
</template>

<script>
// import animated from 'animate.css' 
export default {
    

}
</script>

<style>
.cn_header{
    margin-top:5vh;
    margin-left: 5%;
    margin-right: 5%;

}


</style>