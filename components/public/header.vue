<template>
    <div class="header " id="header" :class="{fixed: isFixed}">
            <div class=" fixed-width clearfix">
            <div class="header-title fl" style="text-align: center">我是顶部</div>
            </div>
    </div>
</template>
 
<script>
import animated from 'animate.css'
export default {
    data () {
    return {
        isFixed: 0
    }
    },
    methods: {
    handleScroll() {
        let top = pageYOffset || document.documentElement.scrollTop || document.body.scrollTop;
        if(top > 250){
            this.isFixed = 1;
        }else if(top < 200){
            this.isFixed = 0;
        }
    },
    handleAnimate() {
        let top = pageYOffset || document.documentElement.scrollTop || document.body.scrollTop;
        let vh = document.documentElement.clientHeight;
        let dom = document.querySelectorAll(".animate");
        [].slice.call(dom).forEach(v => {
            if(top + vh > v.offsetTop){
                var delay = v.dataset.delay;
                if(delay){
                    setTimeout(() => {
                        v.style.opacity = 1;
                        v.classList.add(v.dataset.ani)
                    }, delay)
                }else{
                    v.style.opacity = 1;
                    v.classList.add(v.dataset.ani)
                }
            }else{
                v.classList.remove(v.dataset.ani)
                v.style.opacity = 0;
            }
        })

    }
    },
    mounted() {
    this.$nextTick(() => {
        this.handleAnimate()//初始化第一次加载时在视口内就执行动画
        addEventListener('scroll', this.handleScroll);
        addEventListener('scroll', this.handleAnimate);

    })
    
    },
    destroyed() {
    removeEventListener('scroll', this.handleScroll);//避免影响其他页面
    removeEventListener('scroll', this.handleAnimate);
    }
}
</script>
 
<style scoped lang="scss">
.header{
    background: green;
    height: 58px;
}
.fixed{
    position: fixed;
    top: 0px;
    z-index: 4;
    width: 1190px;
    animation: slideInDown .5s;
    
}
.content{
    height: 2000px;
    background: pink;
    overflow: hidden;
    .banner{
        width: 80%;
        height: 400px;
        background:orange;
        margin: 80px auto;
    }
    .slide{
        font-size: initial;
        height: 100px;
    }
    .bounce{
        width: 80%;
        margin:0 auto 80px;
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        &>div{
            height: 120px;
            float: left;
            width: 45%;
        }
        .yellow{
            background:yellow;
            margin-bottom: 40px;
        }
        .red{
            background:red;
        }
        .green{
            background:green;
        }
        .blue{
            background:blue;
        }
    }
    .zoom{
        width: 80%;
        margin:0 auto 80px;
        display: flex;
        justify-content: space-between;
        &>div{
            width: 23%;
            height: 263px;
        }
        .one{
            background:url(http://www.codingke.com/themes/codingnew-1/img/study/python/python_block1_img1.jpg) no-repeat center/100%;
        }
        .two{
            background:url(http://www.codingke.com/themes/codingnew-1/img/study/python/python_block1_img2.jpg) no-repeat center/100%;
        }
        .three{
            background:url(http://www.codingke.com/themes/codingnew-1/img/study/python/python_block1_img3.jpg) no-repeat center/100%;
        }
        .four{
            background:url(http://www.codingke.com/themes/codingnew-1/img/study/python/python_block1_img4.jpg) no-repeat center/100%;
        }
    }
}
 
</style>
