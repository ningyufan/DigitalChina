<template>
    <div class="gx_box6">
        <div class="tab">
            数字广西
        </div>
        <div class="box6_con" aos = "zoom-in-down">
            <div class="con_nav">
                <div @click="box6_lock = 0">数字政府</div>
                <div @click="box6_lock = 1">数字社会</div>
                <div @click="box6_lock = 2">数字经济</div>
            </div>
            <div class="con_info">
                <template v-if="box6_lock == 0">
                    <div>
                        <h2>数字政府</h2>
                        <ul>
                            <li><a href="/gx_content1" target="_blank">一图看懂数字广西建设大会</a></li>
                            <li><a href="/gx_content2" target="_blank">广西数字政务一体化平台“一窗通”上线试运行 全面提升开办企业效率</a></li>
                            <li><a href="/gx_content3" target="_blank">结伴相行 合力攻坚——全区政务数据“聚通用”攻坚在行动</a></li>
                        </ul>
                    </div>
                </template>
                <template v-if="box6_lock == 1">
                    <div>
                        <h2>数字社会</h2>
                        <ul>
                            <li><a href="/gx_content4" target="_blank">广西将实施“壮美广西·智慧广电”工程</a></li>
                            <li><a href="/gx_content5" target="_blank">“五一”旅游新体验：广西最美海岛开通移动5G网络</a></li>
                            <li><a href="/gx_content6" target="_blank">全国首个5G华为数字小镇在钦州启动</a></li>
                        </ul>
                    </div>
                </template>
                <template v-if="box6_lock == 2">
                    <div>
                        <h2>数字经济</h2>
                        <ul>
                            <li><a href="/gx_content7" target="_blank">“数字+”赋能广西经济和社会高质量发展</a></li>
                            <li><a href="/gx_content8" target="_blank">中国携手东盟加速拥抱数字经济</a></li>
                            <li><a href="/gx_content9" target="_blank">打造数字经济龙头企业 引领数字广西建设新发展</a></li>
                        </ul>
                    </div>
                </template>                              
            </div>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {
            
            box6_lock:0,
        }
    },
}
</script>

<style>
.gx_box6 {
    width: 100vw;
    height: 100vh;
    background-image: url(../../assets/images/gx/bg7.jpg);
    background-size: 100% 100%; 
    
}
.gx_box6 .tab {
    width: 100vw;
    height: 15vh;
    line-height: 15vh;
    text-align: center;
    font-size: 5vh;
    color: rgb(48, 189, 245);
    
}
.gx_box6 .tab:hover {
    animation: tab_scale 1s linear 3;
}

@keyframes tab_scale{
    33.3%{
        font-size: 5vh;
    }
    66.6%{
        font-size: 5.5vh;
    }
    99.9%{
        font-size: 5vh;
    }
}
.gx_box6 .box6_con {
    width: 80vw;
    height: 80vh;
    margin: 0 auto;
    background-color: rgba(0, 0, 0,0.5);
    box-shadow: 2vh 1vw 5px black;
    position: relative;
    background-image: url(../../assets/images/gx/box7_bgpic.png);
    background-size: 100% 100%;
}
.gx_box6 .box6_con .con_nav {
    width: 25vw;
    height: 80vh;
    padding-top: 8vh;
    position: absolute;
    left: 0;
    top: 0;
    /* background-color: rebeccapurple; */
}
.gx_box6 .box6_con .con_nav div{
    height: 20vh;
    width: 21vw;
    margin: 2vh auto;
    /* background-color: #21BBFE;  */
    border-radius: 40px;
    line-height: 14vh;
    text-align: center;
    font-size: 4vh;
    color:white
}
.gx_box6 .box6_con .con_nav div:hover {
    color: #21BBFE; 
}

.gx_box6 .box6_con .con_info {
    width: 50vw;
    height: 70vh;
    position: absolute;
    left: 27.5vw;
    top: 5vh;
    overflow: auto;
    /* background-color: red; */
}
.gx_box6 .box6_con .con_info h2 {
    margin: 0;
    color: white;
}
.gx_box6 .box6_con .con_info ul {
    margin: 3vh  0;
}
.gx_box6 .box6_con .con_info li {
    margin: 0;
    line-height: 8vh;
    font-size: 3vh;
    list-style-image: url(../../assets/images/gx/list_style.png);
    background-size: 100% 100%;
}
</style>