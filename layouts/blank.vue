<template>
    <div>
        <el-container>
        <el-header>
            <Header/>
        </el-header>
        <el-main>
            <nuxt />
        </el-main>
        <el-footer>
            <Footer/>
        </el-footer>
        </el-container>
    </div>
</template>

<script>
import Header from '../pages/header/header.vue'
import Footer from '../pages/footer/footer.vue'
export default {
    components:{
        Header,
        Footer,
    }

}
</script>

<style>
.el-header,.el-main,.el-footer{
    width: 1190px;
    margin: 0 auto;
    padding: 0;
    overflow: unset;
}


</style>
