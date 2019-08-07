<template>
  <div class="chinese-index">
	  <div class="bs-docs-header bs-docs" tabindex="-1" >
      <canvas id="J_dotLine" class="J_dotLine"></canvas>
    </div>
	  <div style="width:1190px">main</div>
    <div class="images">
      <div class="warp-mask">         
        <div class="warp-color">
          <span class="warp-text">洛天依/吃货公主殿下</span>
        </div>
      </div>
      <div class="warp-mask2">         
        <div class="warp-color2">
          <span class="warp-text2">洛天依/吃货公主殿下</span>
        </div>
      </div>
    </div>	
  </div>
</template>
 
<script>
import animated from 'animate.css'
export default {
	layout:'blank',
	head:{
        script:[
            {src:'https://cdn.bootcss.com/jquery/1.12.4/jquery.min.js'},
            {src:'http://120.79.217.74:8081/js/lizi.js'}
        ]
    }

}
</script>
 
<style scoped lang="scss">
.chinese-index{
	text-align: center;
}
.bs-docs{
	background-color: #6fc3df;
	height:180px;
}
.J_dotLine{
	height:176px;
	width:1190px;
}
.images{
  padding: 0px 50px;
}
.warp-mask{
    display: flex;
    align-items: center;
    justify-content: center;
    position:relative;
    background:url(../assets/images/1.jpg)no-repeat;
    background-size:cover;
    background-position: center;
    height:330px;
    width:640px;
    float: left;
}
.warp-color{
    background: rgb(226, 43, 43);
    opacity: 0.8;
    height:330px;
    width:640px;
    text-align: center

}
.warp-color:hover{
    background: none;
}
.warp-text{
  font-size: 30px;
  font-family:'Times New Roman', Times, serif;
  color: white;
  line-height: 300px;

}
.warp-mask2{
    display: flex;
    align-items: center;
    justify-content: center;
    position:relative;
    background:url(../assets/images/3.jpg)no-repeat;
    background-size:cover;
    background-position: center;
    height:330px;
    width:445px;
    float: right;
}
.warp-color2{
    background: blueviolet;
    opacity: 0.8;
    height:330px;
    width:445px;
    text-align: center
}
.warp-color2:hover{
    background: none;
}
.warp-text2{
  font-size: 30px;
  font-family:'Times New Roman', Times, serif;
  color:yellow;
  line-height: 300px;
}
</style>
