<template>
  <div class="chinese-index">
	  <div class="bs-docs-header bs-docs" tabindex="-1" >
        <canvas id="J_dotLine" class="J_dotLine"></canvas>
      </div>
	  main	
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
	height:180px;
	width:1190px;
}
</style>
