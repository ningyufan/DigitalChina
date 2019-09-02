<template>
    <div class="gx_box6">
        <div class="tab" aos = "zoom-in">
            Digital Guangxi
        </div>
        <div class="box6_con" aos = "zoom-in-down">
            <div class="con_nav">
                <div @click="box6_lock = 0">Digital Government</div>
                <div @click="box6_lock = 1">Digital Society</div>
                <div @click="box6_lock = 2">Digital Economy</div>
            </div>
            <div class="con_info">
                <template v-if="box6_lock == 0">
                    <div>
                        <h2>Digital Government</h2>
                        <ul>
                            <li><a href="/e_gx_content1" target="_blank">Understanding Digital Guangxi Construction Congress in One Picture</a></li>
                            <li><a href="/e_gx_content2" target="_blank">On-line Trial Operation of Guangxi Digital Government Integration Platform "One Window Through" to Enhance the Efficiency of Starting Enterprises in an All-round Way</a></li>
                            <li><a href="/e_gx_content3" target="_blank">Collaboration and joint efforts to tackle the key problems -- "gathering and universalizing" the government affairs data in the whole region is taking action to tackle the key problems</a></li>
                        </ul>
                    </div>
                </template>
                <template v-if="box6_lock == 1">
                    <div>
                        <h2>Digital Society</h2>
                        <ul>
                            <li><a href="/e_gx_content4" target="_blank">Guangxi will carry out the project of "Majestic Guangxi, Wisdom Radio and Television"</a></li>
                            <li><a href="/e_gx_content5" target="_blank">New Experience of "May Day" Tourism: Opening Mobile 5G Network in the Most Beautiful Island of Guangxi</a></li>
                            <li><a href="/e_gx_content6" target="_blank">The First 5G Huawei Digital Town in China Started in Qinzhou</a></li>
                        </ul>
                    </div>
                </template>
                <template v-if="box6_lock == 2">
                    <div>
                        <h2>Digital Economy</h2>
                        <ul>
                            <li><a href="/e_gx_content7" target="_blank">"Digital +" Enables the Economic and Social Development of Guangxi with High Quality</a></li>
                            <li><a href="/e_gx_content8" target="_blank">China Hands in Hand with ASEAN to Accelerate Embracing Digital Economy</a></li>
                            <li><a href="/e_gx_content9" target="_blank">Creating leading enterprises of digital economy to lead the new development of digital Guangxi construction</a></li>
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
    text-align: justify;
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