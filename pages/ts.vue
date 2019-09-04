<template>
    <div class="cn_bg">
        <div class="bg_row1">
            <div class="cn_rightheader">
                <div class="right_headerimg1">
                    <span>"数字社会"运行状态的四个特征</span>
                </div>
                
            </div>
            <div class="popOutBg"></div>
            <div class="popOut">
                <span title="关闭"> x </span>
            </div>
            <div class="cn_leftheader">
                <div class="left_headerimg1">
                    <span>数字经济影响城市未来竞争格局</span>
                </div>
            </div>
        </div>
        <div class="fk"><img src="../assets/images/dchina/cfk.png" height="100%" alt=""></div>
        <div class="bg_row2">
            <div class="cn_rightheader">
                <div class="right_headerimg21">
                    <span>共享机遇</span>
                </div>
                <div class="right_headerimg22">
                    <span>融合贯通</span>
                </div>
            </div>
            <div class="cn_leftheader">
                <div class="left_headerimg21">
                    <span>隐忧浮现</span>
                </div>
                <div class="left_headerimg22">
                    <span>发展前景</span>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    head:{
         script:[
            {src:'js/ts.js'},]
    }
    
}
</script>

<style>
.cn_bg{
    position: absolute;
    width: 100vw;
    height: 100vh;
}

.bg_row1,.bg_row2{
    margin-left: 10vw;
    width: 80vw;
    height: 40vh;
}

.cn_rightheader{
    position: relative;  
    float: left;
    width: 40vw
}

.cn_leftheader{
    position: relative;
    float: right;
    width: 40vw;
}

.right_headerimg1{
    height: 40vh;
    width: 40vw;
    background-image: url('../assets/images/dchina/china_mk1.png');
    background-size: 100% 100%;
}
.left_headerimg1{
    height: 40vh;
    width: 40vw;
    background-image: url('../assets/images/dchina/china_mk2.png');
    background-size: 100% 100%;
}

.fk{
     width: 100%;
    height: 8%;
    margin: 0 auto;
    padding-left: 47%;
}

.right_headerimg21{
    height: 40vh;
    width: 20vw;
    float: left;
    background-image: url('../assets/images/dchina/china_mk3.png');
    background-size: 100% 100%;
}

.right_headerimg22{
    height: 40vh;
    width: 20vw;
    float: right;
    background-image: url('../assets/images/dchina/china_mk4.png');
    background-size: 100% 100%;
}

.left_headerimg21{
    height: 40vh;
    width: 20vw;
    float: left;
    background-image: url('../assets/images/dchina/china_mk5.png');
    background-size: 100% 100%;
}

.left_headerimg22{
    height: 40vh;
    width: 20vw;
    float: right;
    background-image: url('../assets/images/dchina/china_mk6.png');
    background-size: 100% 100%;
}


.bg_row1 span,.bg_row2 span{
    position: absolute;
    width: 35vw;
    font-size:4vh;
    margin-left: 8vw;
    bottom: 20vh;
    color: rgb(48, 189, 245);
    font-family: STXingkai;
    text-shadow: -2px 0px 2px
}


.popOutBg{ width:100%; height:100%; position: fixed; left:0; top:0; background:rgba(0,0,0,.6); display: none;}
.popOut{ position:fixed; width:600px; height:300px; top:50%; left:50%; margin-top:-150px; margin-left:-300px; background:#fff; border-radius:8px; overflow: hidden; display: none;}
.popOut > span{ position: absolute; right:10px; top:0; height:42px; line-height:42px; color:#000; font-size:30px; cursor: pointer;}
.popOut table{ display: block; margin:42px auto 0; width:520px;}
.popOut caption{ width:520px; text-align: center; color:#f40; font-size:18px; line-height:42px;}
.popOut table tr td{ color:#666; padding:6px; font-size:14px;}
.popOut table tr td:first-child{ text-align: right;}
@keyframes ani{
	from{
		transform:translateX(-100%) rotate(-60deg) scale(.5);
	}
	50%{
		transform:translateX(0) rotate(0) scale(1);
	}
	90%{
		transform:translateX(20px) rotate(0) scale(.8);
	}
	to{
		transform:translateX(0) rotate(0) scale(1);
	}
}
.ani{ animation:ani .5s ease-in-out;}


</style>