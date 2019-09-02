<template>
    <div class="gx_box4">
        <div class="tab">
			Intelligent Agriculture
        </div>
        <div class="box4_con1">
            <div class="con1_info" aos = "zoom-out-right">
                <div class="info_t">Sunshine Rose Vineyard</div>
                <p>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Dongli Village, Wuzhuan Town, Donglan County is the first Sunshine Rose Vineyard in the county. Intelligent Agricultural Cloud Information and Wuzhuan Town jointly launched the Grape Housekeeping Industry Poverty Alleviation Demonstration Park.
With the support and guidance of Donglan County Government, cooperatives provide land and poor local households participate in the work of vineyard farming. Intelligent Agricultural Cloud Information Utilization of "Grape Housekeeper"
Standardized production platform, from pre-natal, mid-natal and post-natal to provide local poor households with soil improvement, planting guidance and sales docking services. The land transfer of the project involves 530 people from 126 households in Dongli Village.
The project dividend covers 223 poor households of 59 families in the village.
                </p>				
            </div>
            <div class="con1_pic" aos = "zoom-out-left"><img src="../../assets/images/gx/gxbox4_pic1.jpg" height="100%" width="100%" alt=""></div>

        </div>
        <div class="box4_con2">
            <div class="con2_info" aos = "zoom-out-left">
                <div class="info_t" >Intelligent Silkworm</div>
                <p>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Guangxi Silkworm Industry Technology Promotion Station got rid of the traditional silkworm rearing mode, and jointly set up a platform of Guangxi Intelligent Silkworm Breeding and Rearing Internet of Things with Huiyun Information to systematize silkworm rearing.
Standardization greatly improves the efficiency of production management, reduces labor and time costs, and minimizes production risks. Guangxi has built the first intelligent Internet of Things monitoring system for silkworm breeding in China.
The system covers the whole process from mulberry tree planting to silkworm breeding, supporting the breeding ability of improved varieties of mulberry more than 100,000 per year.
                </p>
                
            </div>
            <div class="con2_pic" aos = "zoom-out-right"><img src="../../assets/images/gx/gxbox4_pic2.jpg" height="100%" width="100%" alt=""></div>

        </div>
        <div class="box4_con3">
            <div class="con3_info" aos = "zoom-out-right">
                <div class="info_t">Ming Ming Orchard</div>
                <p>
                    &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Mingming Orchard uses artificial intelligence technology to scientifically predict agricultural production, to carry out beneficial practices in organic cultivation and comprehensive cultivation, and to track, screen and cultivate excellent citrus varieties at home and abroad.
To the application of green preservation technology, build and improve their own technical system, cultivate delicious, nutritious, healthy high-quality products, provide experience and traceable high-quality services. At the same time,
The company has penetrated into post-harvest sorting, cold chain and trade of fruits, perfected the whole industrial chain, and become the principal service provider of citrus industry chain in Guangxi. At present,
"Ming Ming Orchard" ranks 81st in Chinese fruit brand value in 2018 and has strong influence in the domestic market.
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
    font-size: 5vh;
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
    /* text-align: justify; */
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