<template>
    <div class="carousel">
        <el-carousel :interval="5000" arrow="always" height="60vh">
            <el-carousel-item v-for="(item,idx) in items" :key="idx">
                <el-row>
                <el-col class="left_col">
                    <div class="detail">
                        <p class="title"><a :href="item.href">{{item.title}}</a></p>
                        <p>{{ item.p }}</p>
                        <hr class="hr" />
                        <ul>
                            <li v-for="(li,idx) in item.li" :key="idx">
                                <a :href="li.li_href">{{ li.li_name }}</a>
                            </li>
                        </ul>
                    </div>   
                </el-col>
                <el-col class="right_col">
                    <!-- {{item.img}} -->
                    <img src="@/assets/images/wuti.png" height="100%" width="100%" alt="">
                </el-col>
            </el-row>
            </el-carousel-item>
        </el-carousel>
    </div>
</template>

<script>
export default {
    props:['items']

}
</script>

<style>

</style>
