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
                <ul v-for="(item, idx) in header_nav" :key="idx">
                   <nuxt-link :to="item.link_to">
                        <li @click="$emit('li_nav',idx)">{{ item.nav_name }}</li>
                    </nuxt-link>
                    <!-- <li><nuxt-link :to="{name:'chinese_index',params:{newsId:1}} " title="">首页</nuxt-link></li>
                    <li><nuxt-link :to="{name:'DigitalChina',params:{newsId:2}}" title="" ></nuxt-link></li>
                    <li><nuxt-link :to="{name:'DigitalGX',params:{newsId:3}}" title=""></nuxt-link></li>    
                    <li><nuxt-link :to="{name:'DigitalYL',params:{newsId:4}}" title=""></nuxt-link></li>
                    <li><nuxt-link :to="{name:'DigitalYS',params:{newsId:5}}" title=""></nuxt-link></li> 
                    <li><nuxt-link :to="{name:'aboutMe',params:{newsId:6}}" title=""></nuxt-link></li> -->
                </ul>
            </div>
        </el-row>
    </div>
</template>

<script>
export default {
    data() {
        return {
            header_nav: [
                {nav_name:'首页', link_to:'chinese_index'},
                {nav_name:'数字中国', link_to:'DigitalChina'},
                {nav_name:'数字广西', link_to:'DigitalGX'},
                {nav_name:'数字玉林', link_to:'DigitalYL'},
                {nav_name:'数字玉师', link_to:'DigitalYS'},
                {nav_name:'关于我们', link_to:'aboutMe'},
            ]
        }
    }

}
</script>

<style>
@import "@/assets/css/index/page_index.css";
</style>
