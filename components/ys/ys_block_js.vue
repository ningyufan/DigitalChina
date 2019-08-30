<template>
    <div class="ysblockjs">
        <div class="title_js">玉林师范——大数据学院</div>
            <div aos="flip-up">
            <div class="box1_js">
                <img src="@/assets/images/ysblock/img1_js.jpg" class="img1_js" height="100%" width="100%">
            </div>
            <div class="box2_js">
                <img src="@/assets/images/ysblock/img2_js.png" class="img2_js" height="100%" width="100%">
            </div>
            <div class="box3_js">
                <img src="@/assets/images/ysblock/img3_js.jpg" class="img3_js" height="100%" width="100%">
            </div>
        </div>
        <div aos="zoom-in-up">
            <div class="text1_js">
                <div class="title1_js">概述</div>
                <div class="text2_js">
                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;玉林师范学院大数据学院、大数据应用创新中心于2017年7月15日揭牌成立,是基于教育部学校规划建设发展中心联合曙光信息产业股份有限公司发起的数据中国“百校工程”产教融合创新项目而设立的。玉林师范学院是首批被教育部确定的数据中国“百校工程”试点院校,也是桂东南地区唯一一所试点院校。</p>
                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;大数据学院、大数据应用创新中心基地占地面积1200平方米,建设有展示厅、多媒体机房、项目实训室、教师科研团队工作室等功能区.已完成投入1300万元，包含设备机房、设备机房配套、各功能区科研、实验实训,教学的配套设备、展厅文宣内容软装修。</p>
                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;大数据学院目前开设计算机科学与技术专业(大数据技术方向)专业,于2016年招生89名, 2017年招生94名。大数据技术方向侧重于培养软件开发，数据挖掘、算法的分析与应用、分布式系统平台搭建维护等方面的应用型人才。2017年7月，申报“数据科学与大数据技术"专业,目前已上报教育部审批。</p>
                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;大数据应用创新中心的核心科研力量是广西高校重点实验室一复杂系统优化与大数据处理重点实验室,目前实验室包含固定研究人员30.人,其中拥有正高职称9人,副高职称9人,具有博士学位教师10人,博士生导师1人,硕士生导师9人。近三年来,实验室成功申报国家自然科学基金项目20余项，广西自然科学基金项目40余项,科研总经费达到1500多万元。</p>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    head:{
        script:[
            {src:'js/jquery.1.7.1.min.js'},
            {src:'js/aos.js'},
        ],
        link: [
            { rel: 'stylesheet', href: 'css/normalize.css' },
            // { rel: 'stylesheet', href: 'css/demo.css' },
            { rel: 'stylesheet', href: 'js/aos.css' },
            { rel: 'stylesheet', href: 'css/styles.css' }
        ]
    },
    mounted(){
        AOS.init({
            easing: 'ease-out-back',
            duration: 500,
			once :false
        });
    },

}
</script>

<style>
@import "@/assets/css/digitalys.css";

</style>