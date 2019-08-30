<template>
    <div class="ysblockxq">
        <div class="title_xq">大数据学院——建设成果</div>
        <div class="box1_xq" aos="fade-up-right">
            <div class="img1_1_xq">
                <img src="@/assets/images/ysblock/img2_xq.png" class="img1_xq" height="100%" width="100%">
            </div>
            <div class="img1_2_xq">
                <img src="@/assets/images/ysblock/img1_xq.png" class="img2_xq" height="100%" width="100%">
            </div>
        </div>
        <div class="text1_xq" aos="fade-up-left">
            <div class="title1_1_xq">专业人才培养方面</div>
            <div class="text1_1_xq">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;计算机科学与技术专业（大数据技术方向）于2016年招生89名，2017年招生94名。大数据技术方向侧重于培养软件开发、数据挖掘、算法的分析与应用、分布式系统平台搭建维护等方面的应用型人才。2017年7月，申报“数据科学与大数据技术”专业，目前已上报教育部审批。2018年9月，正式招收“数据科学与大数据技术”专业学生。</div>
        </div>
        <div class="box2_xq" aos="fade-up-left">
            <div class="img2_1_xq">
                <img src="@/assets/images/ysblock/img3_xq.jpg" class="img3_xq" height="100%" width="100%">
            </div>
            <div class="img2_2_xq">
                <img src="@/assets/images/ysblock/img4_xq.jpg" class="img3_xq" height="100%" width="100%">
            </div>
        </div>
        <div class="text2_xq" aos="fade-up-right">
            <div class="title1_2_xq">硬件建设方面</div>
            <div class="text1_2_xq">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;大数据基地占地面积1200平方米，建设有展示厅、多媒体机房、项目实训室、教师科研团队工作室等功能区。已完成投入1300万元，包含设备机房、设备机房配套、各功能区科研、实验实训、教学的配套设备、展厅文宣内容软装修等。服务器机房目前拥有104个服务器节点，其中主服务器具备9984流处理能力（GPD），服务器总体数据存储规模达到600TB，并行计算能力达到3000核。采用集中管控的“大数据应用超级系统-Infinity 9000”。</div>
        </div>

        <div class="hx-box pa" id="zindex">
            <ul class="pr">
                <li class="hx-k1 pa0">
                    <span></span>
                </li>
                <li class="hx-k2 pa0">
                    <span></span>
                </li>
                <li class="hx-k3 pa0">
                    <span></span>
                </li>
            </ul>
        </div>

    </div>
</template>

<script>
export default {
    head:{
        script:[
            // {src:'js/index_ys5.js'},
        ],
        link:[
            { rel: 'stylesheet', href: 'css/lib_ys3.css' },
            { rel: 'stylesheet', href: 'css/tabris_ys3.css' }
        ]
    }
    
}
</script>

<style>
.ysblockxq{
    background-image: url(../../assets/images/ysblock/background6.jpg);
    background-size: cover;
    height: 150vh;
    filter:brightness(80%);
}
.zindex{
    position: relative;
    z-index: 2;
}
.title_xq{
    height: 15vh;
    width: 40%;
    margin-left: 30%;
    text-align: center;
    font-size: 5vh;
    color: rgb(51, 135, 214);
    bottom: 0;
    line-height: 11vh;
}
.box1_xq{
    height: 58vh;
    width: 35%;
    /* background-color: rgba(255, 255, 255, 0.6); */
    margin-left: 10%;
    position: relative;
    float: left;
    z-index: 3;
}
.img1_1_xq{
    height: 35vh;
    width: 90%;
    z-index: 1;
    position: absolute;
    border: 2px double #ccc;
    box-shadow: 5px 3px 3px #111;
    filter:brightness(90%);
}
.img1_2_xq{
    height: 30vh;
    width: 75%;
    bottom: 0;
    right: 0;
    z-index: 2;
    position:absolute;
    border: 3px double #ccc;
    box-shadow: 5px 3px 3px #111;
    filter:brightness(90%);
}
.text1_xq{
    height: 40vh;
    width: 38%;
    margin-right: 10%;
    float: right;
    background-color: rgba(255, 255, 255, 0.6);
    margin-top: 9vh;
    padding: 2vh 3%;
    z-index: 3;
    position: relative;
}
.title1_1_xq{
    text-align: center;
    font-size: 4vh;
}
.text1_1_xq{
    font-size: 2.5vh;
    line-height: 4vh;
    padding: 1vh 0;
}
.box2_xq{
    margin-top: 15vh;
    height: 58vh;
    width: 35%;
    /* background-color: rgba(255, 255, 255, 0.6); */
    margin-right: 10%;
    position: relative;
    float: right;
    z-index: 3;
}
.img2_1_xq{
    height: 35vh;
    width: 90%;
    right: 0;
    z-index: 1;
    position: absolute;
    border: 2px double #ccc;
    box-shadow: -5px 3px 3px #111;
    filter:brightness(90%);
}
.img2_2_xq{
    height: 30vh;
    width: 75%;
    bottom: 0;
    left: 0;
    z-index: 2;
    position:absolute;
    border: 3px double #ccc;
    box-shadow: -5px 3px 3px #111;
    filter:brightness(90%);
}
.text2_xq{
    height: 45vh;
    width: 38%;
    margin-left: 10%;
    float: left;
    background-color: rgba(255, 255, 255, 0.6);
    margin-top: 13vh;
    padding: 2vh 3%;
    z-index: 3;
    position: relative;

}
.title1_2_xq{
    text-align: center;
    font-size: 4vh;
}
.text1_2_xq{
    font-size: 2.5vh;
    line-height: 4vh;
    padding: 1vh 0;
}
</style>