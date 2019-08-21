<template>
    <div class="back2_ys">
        <div class="title2_ys">大数据——发展足迹</div>
        <div class="boxs1_ys" aos="fade-up">
            <div class="img_16_ys">
                <img src="../assets/images/ysblock/ys4.png" class="img16_ys" height="100%" width="100%">
            </div>
            <div class="title_1_ys">标题1</div><hr class="hr1_ys">

        </div>
        <div class="boxs2_ys" aos="fade-up">
            <div class="img_16_ys">
                <img src="../assets/images/ysblock/ys4.png" class="img16_ys" height="100%" width="100%">
            </div>
            <div class="title_1_ys">标题2</div><hr class="hr1_ys">
            

        </div>
        <div class="boxs3_ys" aos="fade-up">
            <div class="img_16_ys">
                <img src="../assets/images/ysblock/ys4.png" class="img16_ys" height="100%" width="100%">
            </div>
            <div class="title_1_ys">标题3</div><hr class="hr1_ys"> 
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
    // destroyed() {
    // AOS.init({
    //     easing: 'ease-out-back',
    //     duration: 5000
    // });
    // },

}
</script>

<style>
.back2_ys{
    background-image: url(../assets/images/ysblock/background1.png);
    background-size: cover;
    height: 150vh;
}
.title2_ys{
    height: 14vh;
    width: 40%;
    bottom: 0;
    font-size: 5vh;
    color: rgb(51, 135, 214);
    margin-left: 30%;
    text-align: center;
    line-height: 11vh;
    /* border: 1px solid red */
}
.boxs1_ys{
    width: 26.7%;
    height: 40vh;
    margin: auto 36.65% auto 36.65%;
    background: #ccc;
    box-shadow: 0px 5px 3px #777;
    padding: 8vh 5vh;
    color: black;
    margin-top: 25vh;
}
.boxs2_ys{
    width: 26.7%;
    height: 40vh;
    margin-left: 10%;
    float: left;
    background: #ccc;
    box-shadow: -5px 5px 3px #777;
    padding: 8vh 5vh;
    color: black;
    margin-top: 10vh;
}
.boxs3_ys{
    width: 26.7%;
    height: 40vh;
    margin-right: 10%;
    float: right;
    background: #ccc;
    box-shadow: 5px 5px 3px #777;
    padding: 8vh 5vh;
    color: black;
    margin-top: 10vh;
}
.title_1_ys{
    text-align: center;
    font-size: 3vh;
    margin-top: 3vh;
}
.hr1_ys{
    margin-top:1vh;

}
.img_16_ys{
    height: 27vh;
    width: 100%;
    border: 2px  ridge #777;
    box-shadow: 3px 3px 3px #777;
    margin-top: -30vh;
    -webkit-box-shadow:0px 0px 30px #555;
}
.img_16_ys:before{
    background-color: #111;
    height: 27vh;
    width: 100%;
    opacity: 1;

}
</style>