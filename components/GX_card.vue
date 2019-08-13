<template>
    <div class="GX_card">
        <el-row class="one_row">
            <el-col class="one_col">
                <img src="../assets/images/kuang1_img.png" height="100%" width="100%" alt="">
                
            </el-col>
            <el-col class="two_col">
                
            </el-col>
        </el-row>
        <el-row class="two_row">
            <img src="../assets/images/center.png" height="150%" alt="">
            
        </el-row>
        <el-row class="three_row">
            <el-col class="t_one_col"></el-col>
            <el-col class="t_two_col"></el-col>
            <el-col class="t_three_col"></el-col>
            <el-col class="t_four_col"></el-col>
        </el-row>
    </div>
</template>

<script>
export default {
   
}
</script>

<style>
    @import "@/assets/css/DigitalGX.css";
.GX_card {
    width: 88%;
    height: 100%;
    margin: 3vh 5vw auto;
}

.one_row, .three_row {
    height: 47%;
    width: 100%;
 
}
.one_col,.two_col {
    height: 100%;
    width: 50%;
    
}
.one_col {
    background-image: url(../assets/images//kuang1.png);
    background-size: 100% 100%;
}
.two_col {
    background-image: url(../assets/images//kuang2.png);
    background-size: 100% 100%;
}
.two_row {
    width: 100%;
    height: 6%;
    margin: 0 auto;
    padding-left: 47%;
}
.t_one_col, .t_two_col, .t_three_col,.t_four_col{
    height: 100%;
    width: 25%;
}
.t_one_col{
    background-image: url(../assets/images//kuang3.png);
    background-size: 100% 100%;
}
.t_two_col {
    background-image: url(../assets/images//kuang4.png);
    background-size: 100% 100%;
}
.t_three_col {
    background-image: url(../assets/images//kuang5.png);
    background-size: 100% 100%;
}
.t_four_col {
    background-image: url(../assets/images//kuang6.png);
    background-size: 100% 100%;
}
</style>
    