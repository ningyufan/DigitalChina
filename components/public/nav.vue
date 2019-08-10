<template>
   <div class="header_nav">
        <el-row class="row_one">
            <div class="ce_nav">
                <a href="#">
                    <i class="el-icon-star-on">中</i>
                </a>
                <a href="#">
                    <i class="el-icon-star-off">英</i>
                </a>
            </div>
        </el-row>
        <el-row class="row_tow">
            <div class="nav">
                <ul>
                    <li><nuxt-link :to="{name:'chinese_index',params:{newsId:1}} " title="">首页</nuxt-link></li>
                    <li><nuxt-link :to="{name:'DigitalChina',params:{newsId:2}}" title="" >数字中国</nuxt-link></li>
                    <li><nuxt-link :to="{name:'DigitalGX',params:{newsId:3}}" title="">数字广西</nuxt-link></li>    
                    <li><nuxt-link :to="{name:'DigitalYL',params:{newsId:4}}" title="">数字玉林</nuxt-link></li>
                    <li><nuxt-link :to="{name:'DigitalYS',params:{newsId:5}}" title="">数字玉师</nuxt-link></li> 
                    <li><nuxt-link :to="{name:'aboutMe',params:{newsId:6}}" title="">关于我们</nuxt-link></li>
                </ul>
            </div>
        </el-row>
    </div>
</template>

<script>
export default {

}
</script>

<style>
@import "@/assets/css/index/page_index.css";
</style>
