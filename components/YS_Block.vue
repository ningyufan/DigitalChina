<template>
    <div class="ysblock">
        <div class="gif_ys">    
            <el-carousel :interval="5000" arrow="never" height="55vh">
                <el-carousel-item v-for="item in list" :key="item">
                    <img :src= item height="100%" width="100%">
                </el-carousel-item>
            </el-carousel>
            <div class="gifbefore_ys"></div>
        </div>
    </div>
</template>

<script>
// import animated from 'animate.css' 
export default {
    data(){
        return{
            list:[
                'git/1.gif',
                'git/2.gif',
                'git/3.gif',
            ]
        }
    }
    

}
</script>

<style>
.gif_ys{
    position: relative;
    margin-top:5vh;
    margin-left: 8%;
    margin-right: 8%;
    z-index: 1;
}

.gifbefore_ys{
    position: absolute;
    /* border: 1px solid red; */
    z-index: 3;
    top: 0;
    height: 55vh;
    width: 100%;
}

</style>