<template>
    <div class="Chinaheader_mk">
        <el-row class="Chinaheader_row1">
            <el-col class="Chinaheader_col1">
                <div style="font-size:28px;margin:12vh 10vh;
                color:#00F5FF;text-shadow: -2px 0px 2px"  @click="TZ_Visible=true">
                    "数字社会"运行状态的四个特征
                </div>
                <el-dialog :visible.sync="TZ_Visible" width="70%">
                    <DigtialTZ/>
                </el-dialog>
            </el-col>
            <el-col class="Chinaheader_col2">
                <center style="font-size:28px;margin-top:12vh; color:#00F5FF">
                <span style="text-shadow: -2px 0px 2px" @click="JZ_Visible=true">
                    数字经济影响城市未来竞争格局
                </span>
                </center>
                <el-dialog :visible.sync="JZ_Visible" width="70%">
                    <DigtialJZ/>
                </el-dialog>
            </el-col>
        </el-row>
        <el-row class="fangkuai wow flipInY" data-wow-duration="1s">
            <img src="@/assets/images/dchina/cfk.png" height="100%" alt="">
        </el-row>
        <el-row class="Chinaheader_row2">
            <el-col class="Chinaheader_col3">
                <center style="font-size:28px;margin-top:12vh; color:#00F5FF">
                <span style="text-shadow: -2px 0px 2px" @click="JY_Visible=true">
                    共享机遇</span>
                </center>
                <el-dialog :visible.sync="JY_Visible" width="70%">
                    <DigtialJY/>
                </el-dialog>
            </el-col>
            <el-col class="Chinaheader_col4">
                <center style="font-size:28px;margin-top:12vh; color:#00F5FF">
                <span style="text-shadow: -2px 0px 2px" @click="GJ_Visible=true">
                    融合贯通</span>
                </center>
                <el-dialog :visible.sync="GJ_Visible" width="70%">
                    <DigtialGJ/>
                </el-dialog>
            </el-col>
            <el-col class="Chinaheader_col5">
                <center style="font-size:28px;margin-top:12vh; color:#00F5FF">
                <span style="text-shadow: -2px 0px 2px" @click="YY_Visible=true">
                    隐忧浮现</span>
                </center>
                <el-dialog :visible.sync="YY_Visible" width="70%">
                    <DigtialYY/>
                </el-dialog>
            </el-col>
            <el-col class="Chinaheader_col6">
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
import DigtialTZ from '../dchina/DigitalChina_tz'
import DigtialJZ from '../dchina/DigitalChina_jz'
import DigtialJY from '../dchina/DigitalChina_jy'
import DigtialGJ from '../dchina/DigitalChina_gj'
import DigtialYY from '../dchina/DigitalChina_yy'
export default {
    components:{
        DigtialTZ,DigtialJZ,DigtialJY,DigtialGJ,DigtialYY
    },
    data(){
        return{
            TZ_Visible: false,JZ_Visible: false,
            JY_Visible: false,GJ_Visible: false,
            YY_Visible: false
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
