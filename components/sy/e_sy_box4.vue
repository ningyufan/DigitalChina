<template>
    <div class="sy_box4">
        <div class="sybox4_t">
            5G时代
        </div>
        <div class='accordion'>
            <ul>
                <li>
                    <div class="li_title"><a target="_blank" href="/sy_content5">5G &nbsp;&nbsp;时间表</a></div>
                    <a target="_blank" href="/e_sy_content5"><img src='@/assets/images/sy/sybox4_pic1.jpg'></a>
                </li>
                <li>
                    <div class="li_title">
                        <a target="_blank" href="/sy_content6">5G &nbsp;&nbsp;标准</a></div>
                    <a target="_blank" href="/e_sy_content6"><img src='@/assets/images/sy/sybox4_pic2.jpg'></a>
                </li>
                <li>
                    <div class="li_title"><a target="_blank" href="/sy_content7">从2G到5G 中国为什么能抹平与世界的差距</a></div>
                    <a target="_blank" href="/e_sy_content7"><img src='@/assets/images/sy/sybox4_pic3.jpg'></a>
                </li>
                <li>
                    <div class="li_title"><a target="_blank" href="/sy_content8">5G &nbsp;&nbsp; 大发声</a></div>
                    <a target="_blank" href="/e_sy_content8"><img src='@/assets/images/sy/sybox4_pic4.jpg'></a>
                </li>
                <li>
                    <div class="li_title"><a target="_blank" href="/sy_content9">2020年5G通信有望商用</a></div>
                    <a target="_blank" href="/e_sy_content9"><img src='@/assets/images/sy/sybox4_pic5.jpg'></a>
                </li>
            </ul>
        </div>
    </div>
</template>


<script>
    export default {
    }
</script>

<style>
.accordion{
    width:80vw;
    height:80vh;
    overflow:hidden;
    margin:0 auto;
    box-shadow:0 0 10px 2px rgba(0,0,0,0.4);
}
.accordion ul{
    width:80vw;
}
.accordion li{
    display:block;
    width:20%;
    height:100%;
    overflow:hidden;
    position:relative;
    float:left;
    border-left:1px solid #aaa;
    box-shadow:0 0 25px 10px rgba(0,0,0,0.4);
	-webkit-transition:all .5s;
	-moz-transition:all .5s;
	-ms-transition:all .5s;
	-o-transition:all .5s;
	transition:all .5s;
}
.accordion li img{
    display:block;
    width:60vw;
    height:80vh;
}
.accordion ul:hover li{
    width:5vw;
}
.accordion ul li:hover{
    width:60vw;
}
.accordion ul li .li_title{
    width:60vw;
    height: 10vh;
    position: absolute;
    left: 0;
    bottom: 0;
    background-color:rgba(0,0,0,0.3);
}
.accordion .li_title a{
    display:block;
    color:#fff;
    font-size:16px;
    padding:20px;
}
</style>