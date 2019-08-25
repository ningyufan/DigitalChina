<template>
    <div class="cn_bg2">
            <div class="container clearfix teachers_b">
                <div class="slide" id="slide">
                    <ul>
                        <li> 
                            <img src="../assets/images/dchina/szjj9.jpg" alt="深圳" title="" /> 
                        </li>
                        <li> 
                            <img src="../assets/images/dchina/szjj10.jpg" alt="浙江" title="浙江"/> 
                        </li>
                        <li> 
                            <img src="../assets/images/dchina/szjj11.jpg" alt="贵阳"  
                            title="http://www.gywb.cn/system/2019/07/25/030114557.shtml"/> 
                        </li>
                        <li> 
                            <img src="../assets/images/dchina/szjj12.jpg" alt="重庆" 
                            title="2018年1月21日上午，重庆两江新区数字经济产业园开园活动在互联网产业园举行。两江新区数字经济产业园总规划面积40.8平方公里，包括照母山片区、水土片区和龙兴片区。
        两江新区数字经济产业园分两期建设。一期规划面积约20.8平方公里，其中照母山片区13平方公里、水土片区4.5平方公里、龙兴片区3.3平方公里。二期拓展区面积约20平方公里，其中龙兴片区10平方公里、水土片区10平方公里，作为产业拓展用地。
        据悉，该产业园将重点发展数字基础型、数字应用型、数字服务型三大类产业。" /> 
                        </li>
                        <li> 
                            <img src="../assets/images/dchina/szjj13.jpg" alt="南京" 
                            title=""/> 
                        </li>
                        <li> 
                            <img src="../assets/images/dchina/szjj14.jpg" alt="福州" 
                             title=""/> 
                        </li>
                    </ul>
                <div class="arrow">
                    <div class="prev"><</div>
                    <div class="next">></div>
                </div>
                </div>
            </div>
    <script src="js/cn_bg2.js"></script>
    </div>
</template>
<script>
export default {
    head:{
        script:[
            {src:'js/jquery.1.7.1.min.js'},
            {src:'js/jquery-1.7.2.min.js'},
            {src:'js/aos.js'},
        ],
        link: [
            { rel: 'stylesheet', href: 'css/normalize.css' },
            // { rel: 'stylesheet', href: 'css/default.css' },
            { rel: 'stylesheet', href: 'css/demo.css' },
            { rel: 'stylesheet', href: 'js/aos.css' },
            { rel: 'stylesheet', href: 'css/styles.css' },
        ]
    },
    
}
</script>


<style>

.teachers_b{
  position:relative;
  margin-top:130px;
}
#slide {
    margin: 0 auto;
    width: 760px;
    height: 330px;
    position: relative;
  }

#slide li {
    position: absolute;
    width:760px;
    display: -webkit-box;
    display: -webkit-flex;
    display: flex;
    align-items: flex-start;
    -webkit-box-align: flex-start;
    -webkit-align-items: flex-start;
    background:#fff;
    overflow:hidden;
    box-shadow: 0 0 20px #1d374d;
}

#slide li img {
    width: 100%;
    height: 100%;
}
.slide_left{
 /* width:240px;*/
}
.slide_right{
 /* width:440px;*/
  padding: 40px;
  -webkit-box-flex: 1;
    -webkit-flex: 1;
    flex: 1;
    min-width: 0;
}
.slide_right h3{
font: 400 30px/18px "Microsoft Yahei";
color:#222222;
}
.slide_right h3 span{
  display:inline-block;
  margin-left:10px;
  font: 400 14px/36px "Microsoft Yahei";
color:#555555;
}
.slide_right p{
  padding:20px 0 30px;
  color:#555555;
    font: 400 14px/24px "Microsoft Yahei";
    border-bottom: 1px solid #dbdbdb;
}
.slide_right dl{
  padding-top:30px;
}
.slide_right dd{
  float: left;
  width:33.3%;
   color:#777;
    font: 400 12px/24px "Microsoft Yahei";

}
.slide_right dd h3{
color:#ff9000;
margin-bottom:20px;
}
.arrow {
   /* display: none;*/
}

.arrow .prev,
.arrow .next {
    position: absolute;
    width: 64px;
    top: 38%;
    z-index: 9;
    font: 700 96px 'simsun';
    opacity: 0.3;
    color: #fff;
    cursor: pointer;
}

.arrow .prev {
    left: -220px;
}

.arrow .next {
    right: -220px;
}

.arrow .prev:hover,
.arrow .next:hover {
    color: #00a0e9;
    opacity: .7;
}




</style>