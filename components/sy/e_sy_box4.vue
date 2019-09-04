<template>
    <div class="sy_box4">
        <div class="sybox4_t" aos="zoom-in">
            5G Era
        </div>
        <div class='accordion'>
            <ul>
                <li>
                    <div class="li_title"><a target="_blank" href="/sy_content5">5G Timetable</a></div>
                    <a target="_blank" href="/e_sy_content5"><img src='@/assets/images/sy/sybox4_pic1.jpg'></a>
                </li>
                <li>
                    <div class="li_title">
                        <a target="_blank" href="/sy_content6">5G Timetable</a></div>
                    <a target="_blank" href="/e_sy_content6"><img src='@/assets/images/sy/sybox4_pic2.jpg'></a>
                </li>
                <li>
                    <div class="li_title"><a target="_blank" href="/sy_content7">Why Can China Smooth the Gap with the World from 2G to 5G</a></div>
                    <a target="_blank" href="/e_sy_content7"><img src='@/assets/images/sy/sybox4_pic3.jpg'></a>
                </li>
                <li>
                    <div class="li_title"><a target="_blank" href="/sy_content8">5G Loud voice</a></div>
                    <a target="_blank" href="/e_sy_content8"><img src='@/assets/images/sy/sybox4_pic4.jpg'></a>
                </li>
                <li>
                    <div class="li_title"><a target="_blank" href="/sy_content9">5G Communications Expected to be Commercial in 2020</a></div>
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
.sy_box4{
  width: 100vw;
  height: 110vh;
}

.sybox4_t{
  font-size: 6vh;
  font-family: STXingkai;
  color: rgb(48, 189, 245);
  z-index:5;
  position: relative;
}
.sybox4_t:hover{
  animation: sybox4_t 1s linear 3;
}

@keyframes sybox4_t{
  33.3%{
      font-size: 4vh;
  }
  66.6%{
      font-size: 4.5vh;
  }
  99.9%{
      font-size: 4vh;
  }
}
.accordion{
    width:80vw;
    height:80vh;
    overflow:hidden;
    margin:0 auto;
    margin-top: 5vh;
    /* margin-bottom: 5vh; */
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
    font-size:4vh;
    line-height: 10vh;
    padding-left: 4vw;
}
</style>