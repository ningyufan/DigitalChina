<template>
    <div class="gx_box6">
        <div class="tab" aos = "zoom-in">
            Digital Guangxi
        </div>
        <div class="box6_con" aos = "zoom-in-down">
            <div class="con_nav">
                <div class="con_nav1">Digital Government
                    <ul class="ul1">
                        <li><a href="/e_gx_content1" target="_blank">Understanding Digital Guangxi Construction Congress in One Picture</a></li>
                        <li><a href="/e_gx_content2" target="_blank">On-line Trial Operation of Guangxi Digital Government Integration Platform "One Window Through" to Enhance the Efficiency of Starting Enterprises in an All-round Way</a></li>
                        <li><a href="/e_gx_content3" target="_blank">Collaboration and joint efforts to tackle the key problems -- "gathering and universalizing" the government affairs data in the whole region is taking action to tackle the key problems</a></li>
                    </ul>
                </div>
                <div class="con_nav2">Digital Society
                    <ul class="ul2">
                        <li><a href="/e_gx_content4" target="_blank">Guangxi will carry out the project of "Majestic Guangxi, Wisdom Radio and Television"</a></li>
                        <li><a href="/e_gx_content5" target="_blank">New Experience of "May Day" Tourism: Opening Mobile 5G Network in the Most Beautiful Island of Guangxi</a></li>
                        <li><a href="/e_gx_content6" target="_blank">The First 5G Huawei Digital Town in China Started in Qinzhou</a></li>
                    </ul>
                </div>
                <div class="con_nav3">Digital Economy
                    <ul class="ul3">
                        <li><a href="/e_gx_content7" target="_blank">"Digital +" Enables the Economic and Social Development of Guangxi with High Quality</a></li>
                        <li><a href="/e_gx_content9" target="_blank">China Hands in Hand with ASEAN to Accelerate Embracing Digital Economy</a></li>
                        <li><a href="/e_gx_content8" target="_blank">Creating leading enterprises of digital economy to lead the new development of digital Guangxi construction</a></li>
                    </ul> 
                </div>
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
    font-size: 6vh;
    font-family: STXingkai;
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

.gx_box6 .box6_con .con_nav1{
    position: absolute;
    top: 8vh;
    z-index: 2;
    float: left;
    left: 10%;

}
.gx_box6 .box6_con .con_nav2{
    position: absolute;
    left: 10%;
    top: 28vh;
    
    
}
.gx_box6 .box6_con .con_nav3{
    position: absolute;
    left: 10%;
    top: 49vh;
}
.gx_box6 .box6_con .con_nav1,
.gx_box6 .box6_con .con_nav2,
.gx_box6 .box6_con .con_nav3{
    height: 20vh;
    width: 21vw;
    margin: 2vh auto;
    line-height: 14vh;
    font-size: 4vh;
    color:white;
}

.gx_box6 .box6_con .ul1{
   position: absolute;
   left: 20vw;
    top: -6vh;
}
.gx_box6 .box6_con .ul2{
   position: absolute;
   left: 20vw;
    top:3vh;
}
.gx_box6 .box6_con .ul3{
   position: absolute;
   left: 20vw;
    top:4vh;

}
.gx_box6 .box6_con li {
    margin: 0;
    width: 50vw;
    line-height: 5vh;
    font-size: 2.5vh;
    list-style-image: url(../../assets/images/gx/list_style.png);
    background-size: 100% 100%;
    float: left;
}
.gx_box6 .box6_con .con_nav1:hover{
    color: aqua;
}
.gx_box6 .box6_con .con_nav1:hover a{
    color: aqua;
}
.gx_box6 .box6_con .con_nav2:hover{
    color: aqua;
}
.gx_box6 .box6_con .con_nav2:hover a{
    color: aqua;
}
.gx_box6 .box6_con .con_nav3:hover{
    color: aqua;
}
.gx_box6 .box6_con .con_nav3:hover a{
    color: aqua;
}
</style>