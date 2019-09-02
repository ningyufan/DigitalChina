<template>
    <div class="gx_box4">
        <div class="tab" aos = "zoom-in">
			智慧农业
        </div>
        <div class="box4_con1">
            <div class="con1_info" aos = "zoom-out-right">
                <div class="info_t">阳光玫瑰葡萄园</div>
                <p>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;东兰县武篆镇东里村是全县第一个阳光玫瑰葡萄园，智慧农业云信息与武篆镇共同启动了葡萄管家产业扶贫示范园，
                由东兰县政府扶持引导，合作社提供土地，当地贫困户参与从事葡萄园农事工作。智慧农业云信息利用“葡萄管家”
                标准化生产平台，从产前、产中、产后为当地贫困户提供土壤改良、种植指导及销售对接服务。项目土地流转涉及东里村群众126户530人，
                项目分红覆盖全村59户贫困户223人。
                </p>				
            </div>
            <div class="con1_pic" aos = "zoom-out-left"><img src="../../assets/images/gx/gxbox4_pic1.jpg" height="100%" width="100%" alt=""></div>

        </div>
        <div class="box4_con2">
            <div class="con2_info" aos = "zoom-out-left">
                <div class="info_t" >智能桑蚕</div>
                <p>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;广西蚕业技术推广总站摆脱传统的养蚕模式，携手慧云信息共同搭建了广西智能桑蚕种养物联网系统平台，让种桑蚕系统化、
                标准化，大大提高了生产管理效率，降低了人工和时间成本，并将生产风险降到最低。广西建设了国内首个用于桑蚕养殖的智能物联网监控系统，
                系统全面覆盖从桑树种植到种蚕养殖全流程，支撑桑蚕良种繁育能力每年10万张以上。
                </p>
                
            </div>
            <div class="con2_pic" aos = "zoom-out-right"><img src="../../assets/images/gx/gxbox4_pic2.jpg" height="100%" width="100%" alt=""></div>

        </div>
        <div class="box4_con3">
            <div class="con3_info" aos = "zoom-out-right">
                <div class="info_t">鸣鸣果园</div>
                <p>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;鸣鸣果园采用人工智能技术，对农业生产进行科学预测，对有机栽培和综合种养进行有益实践，从国内外优良柑橘品种的追踪、筛选、培育，
                到绿色保鲜技术的应用，搭建完善自身的技术体系，培育出好吃、营养、健康的优质产品，提供可体验和追溯的优质服务。同时，
                该企业深度切入水果采后分选处理、冷链和贸易，完善整个产业链，成为广西柑橘全产业链的首席服务商。目前，
                “鸣鸣果园”品牌位列2018中国果品品牌价值第81位，在国内市场具有较强的影响力
                </p>
                
            </div>
            <div class="con3_pic" aos = "zoom-out-left"><img src="../../assets/images/gx/gxbox4_pic3.jpg" height="100%" width="100%" alt=""></div>

        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.gx_box4 {
    width: 100vw;
    height: 160vh;
    background-image: url(../../assets/images/gx/bg5.jpg);
    background-size: 100% 100%; 
    position: relative;
}
.gx_box4 .tab {
    width: 100vw;
    height: 15vh;
    line-height: 15vh;
    text-align: center;
    font-size: 6vh;
    font-family: STXingkai;
    color: rgb(48, 189, 245);
    
}
.gx_box4 .tab:hover {
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
.box4 .box4_an {
    height: 100vh;
    width: 100vw;
    position: absolute;
    left: 0;
    top: 0;
}
.gx_box4 .box4_con1, 
.gx_box4 .box4_con2,
.gx_box4 .box4_con3{
    height: 48vh;
    width: 80vw;
    margin: 0 auto;
    /* background-color: aqua; */
    position: relative;
    
}
.gx_box4 .box4_con1 .con1_info,
.gx_box4 .box4_con3 .con3_info
{
    height: 44vh;
    width: 60vw;
    background-color: rgba(255, 255, 255, 0.5);
    position: absolute;
    left: 0;
    top: 0;
    padding:6vh 8vw 6vh 5vw;
    box-shadow: 1vw 1vh 2px black ;
}
.gx_box4 .box4_con1 .con1_info .info_t,
.gx_box4 .box4_con3 .con3_info .info_t
{
    height: 6vh;
    width: 47vw;
    position: absolute;
    left: 5vw;
    top: 6vh;
    line-height: 6vh;
    text-align: center;
    font-size: 20px;
}
.gx_box4 .box4_con1 .con1_info p,
.gx_box4 .box4_con3 .con3_info p
{
    height: 26vh;
    width: 47vw;
    position: absolute;
    left: 5vw;
    top: 12vh;

}

.gx_box4 .box4_con1 div:nth-child(2),
.gx_box4 .box4_con3 div:nth-child(2)
{
    height: 30vh;
    width: 20vw;
    background-color: blue;
    position: absolute;
    
    left: 57vw;
    top: 10vh;
    box-shadow: 1vw 1vh 2px black ;
}

.gx_box4 .box4_con2 .con2_info
{
    height: 44vh;
    width: 60vw;
    position: absolute;
    right: 2vw;
    padding:6vh 5vw 6vh 8vw;
    background-color:rgba(255, 255, 255, 0.5);
    box-shadow: 1vw 1vh 2px black ;
    
}
.gx_box4 .box4_con2 .con2_info .info_t
{
    height: 6vh;
    width: 47vw;
    position: absolute;
    right: 5vw;
    top: 6vh;
    line-height: 6vh;
    text-align: center;
    font-size: 20px;
}
.gx_box4 .box4_con2 .con2_info p
{
    height: 26vh;
    width: 47vw;
    position: absolute;
    right: 5vw;
    top: 12vh;

}
.gx_box4 .box4_con2 div:nth-child(2)
{
    height: 30vh;
    width: 20vw;
    background-color: blue;
    position: absolute;
    right: 57vw;
    top: 10vh;
    box-shadow: 1vw 1vh 2px black ;
}
</style>