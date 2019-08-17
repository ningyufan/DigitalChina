<template>
    <div>
        <div class="yulin_bk">
            <div class="yulin_bk_1">
                <el-row class="module2_1">
                    <el-col :span="12">
                        <ul class="icon1">
                            <li v-for="(li_item_1,idx1) in li_items_1" :key="idx1" class="yl_text1">
                                <el-image :src=li_item_1.img></el-image>
                                <a class="style_a" href="">{{li_item_1.li_value}}</a>
                            </li>
                        </ul>
                    </el-col>

                    <el-col :span="12">
                        <ul class="icon1">
                            <li v-for="(li_item_2,idx2) in li_items_2" :key='idx2' class="yl_text1">
                                    <img :src=li_item_2.img alt="" />
                                    <a href="">{{li_item_2.li_value}}</a>
                            </li>
                        </ul>
                    </el-col>

                </el-row>

                <el-row :gutter="20" class="module2_2" >
                    <el-col :span="5" class="img2_1"></el-col>
                    <el-col :span="7" class="img2_2"></el-col>
                    <el-col :span="5" class="img2_3"></el-col>
                    <el-col :span="5" class="img2_4"></el-col>
                    <!-- <el-col :span="6" v-for="(img_item,idx2) in img_items_2" :key="idx2" class="container"> 
                        <img :src=img_item.img alt=""/>
                    </el-col> -->
                </el-row>
            </div>
            <div class="yulin_bk_2">
                <el-col :span="12" class="module3_1">
                    <ul class="icon1">
                        <li class="yl_text1" v-for="(li_item_3,idx3) in li_items_3" :key="idx3">
                            <img :src=li_item_3.img alt="">
                            <a href="" >{{li_item_3.li_value}}</a>
                        </li>
                    </ul>
                </el-col>

                <el-col :span="12" class="module3_2"></el-col>
            </div>    
        </div>

    </div>


</template>


<script>
export default {
    layout:'blank',
    components:{
        
        },
    data(){
        return{
            li_items_1:[
                {img:require("@/assets/images/yulin/fangkuai.png"),li_value:'借力“互联网+”玉林中药港“大数据”'},
                {img:require("@/assets/images/yulin/fangkuai.png"),li_value:'玉林中药材走向信息化大型平台交易，药商不出门，药材满八方'},
                {img:require("@/assets/images/yulin/fangkuai.png"),li_value:'重磅！5G来玉林了！玉林开通首个5G城市实验网'},
            ],

            li_items_2:[
                {img:require("@/assets/images/yulin/fangkuai.png"),li_value:'玉林市大数据发展和政务服务局：从“能够办”向“简易办”转变”'},
                {img:require("@/assets/images/yulin/fangkuai.png"),li_value:'玉林一年到底有多少交通违法行为？交通“大数据”来告诉你”'},
                {img:require("@/assets/images/yulin/fangkuai.png"),li_value:'玉林市博白县运用“大数据”盯住民生资金”'},
            ],
            // img_items_2:[
            //     {img:require("@/assets/images/yulin/picture4.png")},
            //     {img:require("@/assets/images/yulin/picture5.png")},
            //     {img:require("@/assets/images/yulin/picture6.png")},
            //     {img:require("@/assets/images/yulin/picture7.png")},
            // ],

            li_items_3:[
                {img:require("@/assets/images/yulin/fangkuai.png"),li_value:'玉林市兴业县“扶贫云”大数据助力扶贫领域监督执纪”'},
                {img:require("@/assets/images/yulin/fangkuai.png"),li_value:'玉林市北流力建农特优产品大数据”'},
                {img:require("@/assets/images/yulin/fangkuai.png"),li_value:'有了旅游大数据平台 智慧旅游好便捷”'},
                {img:require("@/assets/images/yulin/fangkuai.png"),li_value:'19名清华大学博士研究生围绕玉林市城市大数据平台的融合与推广等15个项目开展社会实践'},
                {img:require("@/assets/images/yulin/fangkuai.png"),li_value:'玉林市召开2019年全市大数据发展和政务服务工作会议 吹响大数据发展号角'},
                {img:require("@/assets/images/yulin/fangkuai.png"),li_value:'玉林市部署大数据发展和政务服务工作:建设数字玉林,服务“东融”战略'},
            ],
        }
    }
}
</script>

<style lang="scss">
    .yulin_bk{
    background-image: url('../assets/images/yulin/yulin_bk.png');
    width: 100vw;
    margin: 0 auto;
    background-size: 100vw 165vh;
    height: 165vh;
}
    .yulin_bk_1{
        background-image: url('../assets/images/yulin/二屏外框.png');
        position: relative;
        width: 100vw;
        margin: 0 auto;
        background-size: 100vw 90vh;
        height: 90vh;
    }

    .yulin_bk_2{
        background-image: url('../assets/images/yulin/三屏外框.png');
        position: relative;
        width: 100vw;
        margin: 0 auto;
        background-size: 100vw 75vh;
        height: 75vh;
    }
    .module2_1{
        margin: auto;
        width: 90vw;
        height: 45vh;
        top:14vh;
    }
    .module2_2{
        position: absolute;
        width: 90vw;
        height: 35vh;
        left: 6vw;
        top: 38vh;
    }
    .module3_1{
        position: absolute;
        left: 3vw;
        width: 45vw;
        height: 40vh;
        top:18vh;
    }
    .module3_2{
        background-image: url('../assets/images/yulin/picture8.png');
        background-size: 100% auto;
        position: absolute;
        right: 3vw;
        width: 45vw;
        height: 50vh;
        margin:auto;
        bottom: 12vh;
    }
    .icon1{
        list-style-type: none;
    }
    .yl_text1{
        width: 50vw;
        height: 8vh;
    }
    .style_a{
        width: 40vw;
        height: 4vh;
    }
    .img2_1{
        margin: 0.5vw;
        height:100%;
        background-size:100% 100%;
        background-repeat: no-repeat;
        background-position: center;
        background-image: url('../assets/images/yulin/picture4.png');
    }
    .img2_2{
        margin: 0.5vw;
        height:100%;
        background-size:100% 100%;
        background-repeat: no-repeat;
        background-position: center;
        background-image: url('../assets/images/yulin/picture5.png');
    }
    .img2_3{
        margin: 0.5vw;
        height:100%;
        background-repeat: no-repeat;
        background-position: center;
        background-size:100% 100%;
        background-image: url('../assets/images/yulin/picture6.png');
    }
    .img2_4{
        /* padding: 0vw; */
        margin: 0.5vw;
        height:100%;  
        background-size:100% 100%;
        background-image: url('../assets/images/yulin/picture7.png');
    }
</style>