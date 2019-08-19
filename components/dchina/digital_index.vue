<template>
    <div class="China_mk">
        <el-row class="China_row1">
            <el-col class="China_col1">
                <center style="font-size:28px;margin-top:12vh;color:#00F5FF">
                <span @click="mk1Visible=true" style="text-shadow: -2px 0px 2px">"数字社会"运行状态的四个特征</span>
                </center>
                <el-dialog :visible.sync="mk1Visible">
                    <DigtialTZ/>
                </el-dialog>
            </el-col>
            <el-col class="China_col2">
                <center style="font-size:28px;margin-top:12vh;color:#00F5FF">
                <span @click="mk2Visible=true" style="text-shadow: -2px 0px 2px">山东省推进工业互联网发展的思考</span>
                </center>
                <el-dialog :visible.sync="mk2Visible">
                    <DigtialSD/>
                </el-dialog>
            </el-col>
        </el-row>
        <el-row class="fangkuai wow flipInY" data-wow-duration="1s">
            <img src="@/assets/images/dchina/cfk.png" height="100%" alt="">
        </el-row>
        <el-row class="China_row2">
            <el-col class="China_col3">
                <center style="font-size:28px;margin-top:12vh;color:#00F5FF">
                <span @click="mk3Visible=true" style="text-shadow: -2px 0px 2px">共享机遇</span>
                </center>
                <el-dialog :visible.sync="mk3Visible">
                    <DigtialJY/>
                </el-dialog>
            </el-col>
            <el-col class="China_col4">
                <center style="font-size:28px;margin-top:12vh;color:#00F5FF">
                <span @click="mk4Visible=true" style="text-shadow: -2px 0px 2px">有力工具</span>
                </center>
                <el-dialog :visible.sync="mk4Visible">
                    <DigtialGJ/>
                </el-dialog>
            </el-col>
            <el-col class="China_col5">
                <center style="font-size:28px;margin-top:12vh;color:#00F5FF">
                <span @click="mk5Visible=true" style="text-shadow: -2px 0px 2px">隐忧浮现</span>
                </center>
                <el-dialog :visible.sync="mk5Visible">
                    <DigtialYY/>
                </el-dialog>
            </el-col>
            <el-col class="China_col6">
                <center style="margin-top:12vh;">
                <span style="text-shadow: -2px 0px 2px">
                    <a href="#" style="font-size:28px;color:#00F5FF">
                    更多</a></span>
                </center>
            </el-col>
        </el-row>
    </div>
</template>

<script>
if (process.browser) { // 在这里根据环境引入wow.js
      var {WOW} = require('wowjs')
  }
//   import animated from 'animate.css'
import DigtialTZ from '../dchina/digital_tz'
import DigtialSD from '../dchina/digital_sd'
import DigtialJY from '../dchina/digital_jy'
import DigtialGJ from '../dchina/digital_gj'
import DigtialYY from '../dchina/digital_yy'
export default {
    components:{
        DigtialTZ,DigtialSD,DigtialJY,DigtialGJ,DigtialYY
    },
    data(){
        return{
            mk1Visible: false,mk2Visible: false,
            mk3Visible: false,mk4Visible: false,
            mk5Visible: false
        }
    },
    mounted: function() {
      if (process.browser) {  // 在页面mounted生命周期里面 根据环境实例化WOW
         new WOW({
             live: false, 
             offset: 0
            }).init()
        }
        // window.scrollReveal=new scrollReveal();
        // window.scrollReveal2=new scrollReveal({elem:document.getElementById('srcontainer')});
        // container.innerHTML(data.newElementHTML);
        // scrollReveal.init();
    }

}
</script>

<style>
    @import "@/assets/css/digital_china.css";
</style>
