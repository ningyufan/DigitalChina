<template>
    <div class="sy_header">
        <div class="syh_info1">
            <div class="syh_t">
                数字中国
            </div>
            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                数字中国旨在以遥感卫星图像为主要的技术分析手段，在可持续发展、农业、资源、环境、全球变化、生态系统、水土循环系统等方面管理中国。
            </p>
        </div>
        <div class="syh_info2">
            <!-- <img src="../../assets/images/sy/1.jpg" height="100%" width="100%" alt=""> -->
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.sy_header {
    height: 60vh;
    width: 100%;
    color:rgb(51, 135, 214);
}
.sy_header .syh_info1,
.sy_header .syh_info2{
    height: 100%;
    width: 50%;
    float: left;
}
.sy_header .syh_info1{
    padding: 5vw 10vw;
}

.syh_t {
    height: 10vh;
    /* width:; */
    text-align: center;
    line-height: 10vh;
    font-size: 5vh;
    /* background-color: aqua; */
}
</style>