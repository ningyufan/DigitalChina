<template>
    <div class="sy_content5">
        <div class="sycon5_t">
            5G时间表
        </div>
        <div class="sycon5_infos">
            <div class="sycon5_info" aos = "fade-up-right">
                <div>
                    中国联通公布了5G部署：将以SA为目标架构，前期聚焦eMBB，5G网络计划2020年正式商用。
                </div>
                <span>2018.06.28</span>
            </div>
            <div class="sycon5_info" aos = "fade-up-left">
                <div>
                3GPP全会（TSG#80）批准了第五代移动通信技术标准（5G NR）独立组网功能冻结。加之2017年12月完成的非独立组网NR标准，5G已经完成第一阶段全功能标准化工作，进入了产业全面冲刺新阶段。
                </div>
                <span>2018.06.14</span>
            </div>
            <div class="sycon5_info" aos = "fade-up-right" >
                <div>
                    3GPP 5G NR标准 SA（Standalone，独立组网）方案在3GPP第80次TSG RAN全会正式完成并发布，这标志着首个真正完整意义的国际5G标准正式出炉。
                </div>
                <span>2018.06.13</span>
            </div>
            <div class="sycon5_info" aos = "fade-up-left" >
                <div>
                    发改委发布《关于组织实施2018年新一代信息基础设施建设工程的通知》，要求2018年将在不少于5个城市开展5G规模组网试点，每个城市5G基站数量不少50个、全网5G终端不少于500个。
                </div>
                <span>2017.12</span>
            </div>
            <div class="sycon5_info" aos = "fade-up-right">
                <div>
                    在国际电信标准组织3GPP RAN第78次全体会议上，5G NR首发版本正式冻结并发布。
                </div>
                <span>2017.12.21</span>
            </div>
            <div class="sycon5_info" aos = "fade-up-left" >
                <div>
                中国工信部发布通知，正式启动5G技术研发试验第三阶段工作，并力争于2018年年底前实现第三阶段试验基本目标。
                </div>
                <span>2017.11</span>
            </div>
            <div class="sycon5_info" aos = "fade-up-right">
                <div>
                工信部发布《关于第五代移动通信系统使用3300-3600MHz和4800-5000MHz频段相关事宜的通知》，确定5G中频频谱，能够兼顾系统覆盖和大容量的基本需求。
                </div>
                <span>2017.11.15</span>
            </div>
            <div class="sycon5_info" aos = "fade-up-left" >
                <div>
                    国际通信标准组织3GPP宣布了“5G”的官方Logo。
                </div>
                <span>2017.02.09</span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    layout:'content2',

}
</script>

<style>
.sycon5_t {
    height: 10vh;
    width: 100%;
    line-height: 10vh;
    font-size: 5vh;
    text-align: center;
    color: rgb(48, 189, 245);
    /* background-color: beige; */
    background-image: url(../assets/images/sy/sycon5_bgb.png);
    background-size: 100% 100%;
}
.sycon5_infos {
    height: 150vh;
    width: 100%;
    padding-top:2vh ;
    /* background-color: rebeccapurple; */
    background-image: url(../assets/images/sy/sycon5_bgb2.png);
    background-size: 100%;
    position: relative;

}
.sycon5_info {
    height: 18vh;
    width:40%;
    /* background-color: bisque; */
    background-image: url(../assets/images/sy/sycon5_bgk.png);
    /* background-repeat:no-repeat; */
    background-size: 100% 100% ;
    color: white;
}
.sycon5_info div {
    margin: 0 10px 0 10px;
}
.sycon5_infos div:nth-child(1) {
    position: absolute;
    left: 0;
    top: 2vh;
}

.sycon5_infos div:nth-child(2) {
    position: absolute;
    right: 0;
    top: 20vh;
}
.sycon5_infos div:nth-child(3) {
    position: absolute;
    left: 0;
    top: 38vh;
}
.sycon5_infos div:nth-child(4) {
    position: absolute;
    right: 0;
    top: 56vh;
}
.sycon5_infos div:nth-child(5) {
   position: absolute;
    left: 0;
    top: 74vh;
}
.sycon5_infos div:nth-child(6) {
    position: absolute;
    right: 0;
    top: 92vh;
}
.sycon5_infos div:nth-child(7) {
    position: absolute;
    left: 0;
    top: 110vh;
}
.sycon5_infos div:nth-child(8) {
    position: absolute;
    right: 0;
    top: 128vh;
}
.sycon5_infos div:nth-child(1) span,
.sycon5_infos div:nth-child(3) span,
.sycon5_infos div:nth-child(5) span,
.sycon5_infos div:nth-child(7) span{
    position: absolute;
    left: 100%;
    margin-left: 2vw;
    line-height: 18vh;
}
.sycon5_infos div:nth-child(2) span,
.sycon5_infos div:nth-child(4) span,
.sycon5_infos div:nth-child(6) span,
.sycon5_infos div:nth-child(8) span{
    position: absolute;
    right: 100%;
    margin-right: 2vw;
    line-height: 18vh;
}
</style>