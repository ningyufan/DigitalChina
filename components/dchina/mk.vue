<template>
    <div class="China_mk">
        <el-row class="China_row1">
            <el-col class="China_col1 wow bounceInLeft">
                <center style="font-size:28px;margin-top:12vh;color:#00F5FF">
                <span @click="mk1Visible=true">"数字社会"运行状态的四个特征</span>
                </center>
                <el-dialog :visible.sync="mk1Visible">
                    <img src="@/assets/images/1.jpg" alt="">
                </el-dialog>
            </el-col>
            <el-col class="China_col2 wow bounceInRight">
                <center style="font-size:28px;margin-top:12vh;color:#00F5FF">
                <span @click="mk2Visible=true">山东省推进工业互联网发展的思考</span>
                </center>
                <el-dialog :visible.sync="mk2Visible">
                    <img src="@/assets/images/3.jpg" alt="">
                </el-dialog>
            </el-col>
        </el-row>
        <el-row class="fangkuai">
            <img src="@/assets/images/dchina/cfk.png" height="100%" alt="">
        </el-row>
        <el-row class="China_row2">
            <el-col class="China_col3 wow bounceInLeft">
                <center style="font-size:28px;margin-top:12vh;color:#00F5FF">
                <span @click="mk3Visible=true">"共享机遇</span>
                </center>
                <el-dialog :visible.sync="mk3Visible">
                    <img src="@/assets/images/1.jpg" alt="">
                </el-dialog>
            </el-col>
            <el-col class="China_col4 wow bounceInRight">
                <center style="font-size:28px;margin-top:12vh;color:#00F5FF">
                <span @click="mk4Visible=true">有力工具</span>
                </center>
                <el-dialog :visible.sync="mk4Visible">
                    <img src="@/assets/images/3.jpg" alt="">
                </el-dialog>
            </el-col>
            <el-col class="China_col5 wow bounceInLeft">
                <center style="font-size:28px;margin-top:12vh;color:#00F5FF">
                <span @click="mk5Visible=true">"隐忧浮现</span>
                </center>
                <el-dialog :visible.sync="mk5Visible">
                    <img src="@/assets/images/1.jpg" alt="">
                </el-dialog>
            </el-col>
            <el-col class="China_col6 wow bounceInRight">
                <center style="margin-top:12vh;">
                <span><a href="#" style="font-size:28px;color:#00F5FF">
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
export default {
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
    }

}
</script>

<style>
    @import "@/assets/css/digital_china.css";
</style>
