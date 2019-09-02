<template>
    <div class="sy_box2" id="sy_box2">
        <div class="sybox2_t" aos="zoom-in">
            数字动态
        </div>
        <div class="sybox2_con">
            <div class="cont s--inactive">
            <!-- cont inner start -->
                <div class="cont__inner">
                    <!-- el start -->
                    <div class="el">
                        <div class="el__overflow">
                            <div class="el__inner">
                            <div class="el__bg"></div>
                            <div class="el__preview-cont">
                                <h2 class="el__heading">福州</h2>
                            </div>
                            <div class="el__content">
                                <div class="el__text">福州：数字中国建设成果展人气火爆</div>
                                <p style="color:white">
                                    本次展览共分为四大展区，有数字福建馆、电子政务馆、数字经济馆、数字社会体验馆，
                                    同时还为数字经济龙头企业安排了新产品、新技术、新应用的发布展台。值得一提的是，
                                    在展馆体验项目众多，观众可以身临其境感觉最新科技带来的便利生活。
                                </p>
                                <div class="el__close-btn"></div>
                            </div>
                            </div>
                        </div>
                        <div class="el__index">
                            <div class="el__index-back">1</div>
                            <div class="el__index-front">
                            <div class="el__index-overlay" data-index="1">1</div>
                            </div>
                        </div>
                    </div>
                    <!-- el end -->
                    <!-- el start -->
                    <div class="el">
                        <div class="el__overflow">
                            <div class="el__inner">
                                <div class="el__bg"></div>
                                <div class="el__preview-cont">
                                    <h2 class="el__heading">5G</h2>
                                </div>
                                <div class="el__content">
                                    <div class="el__text">5G推动万物互联</div>
                                    <p style="color:white">
                                        5G拥有此前几代网络技术都无法达到的能力，5G能够让网络超越人与人的互联，
                                        让数十亿计的物物互联并实时、可靠地操控机器。
                                    </p>
                                    <div class="el__close-btn"></div>
                                </div>
                            </div>
                        </div>
                        <div class="el__index">
                            <div class="el__index-back">2</div>
                            <div class="el__index-front">
                                <div class="el__index-overlay" data-index="2">2</div>
                            </div>
                        </div>
                    </div>
                    <!-- el end -->
                    <!-- el start -->
                    <div class="el">
                        <div class="el__overflow">
                            <div class="el__inner">
                                <div class="el__bg"></div>
                                <div class="el__preview-cont">
                                    <h2 class="el__heading">无人机</h2>
                                </div>
                                <div class="el__content">
                                    <div class="el__text">京东展出的第三代配送机器人</div>
                                    <p style="color:white">
                                        京东展示了Y3无人机和倾转旋翼无人机。倾转旋翼无人机长3.42米、高1.13米、翼展3.78米，个头几乎是Y3无人机的3倍。
                                        这款机器人不仅外形可爱，功能也很强大。它以自动驾驶核心技术为基础，有8个大小不同的载货舱，可按照既定路线自动导航行驶，
                                        可以对城市环境下高校、办公楼、小区等订单集中场所进行批量送货，出色的灵活性和便捷的使用流程将大幅提升配送效率。
                                    </p>
                                    <div class="el__close-btn"></div>
                                </div>
                            </div>
                        </div>
                        <div class="el__index">
                            <div class="el__index-back">3</div>
                            <div class="el__index-front">
                                <div class="el__index-overlay" data-index="3">3</div>
                            </div>
                        </div>
                    </div>
                    <!-- el end -->
                    <!-- el start -->
                    <div class="el">
                        <div class="el__overflow">
                            <div class="el__inner">
                                <div class="el__bg"></div>
                                <div class="el__preview-cont">
                                    <h2 class="el__heading">人工智能</h2>
                                </div>
                                <div class="el__content">
                                    <div class="el__text">人工智能重塑机器人产业</div>
                                    <p style="color:white">
                                        人工智能和新一代信息技术正在重塑机器人产业，技术和应用的拓展、供给和需求的扩大，
                                        使得机器人产业仍然是推动新旧动能转换和经济高质量发展的重要动力。
                                    </p>
                                    <div class="el__close-btn"></div>
                                </div>
                            </div>
                        </div>
                        <div class="el__index">
                            <div class="el__index-back">4</div>
                            <div class="el__index-front">
                                <div class="el__index-overlay" data-index="4">4</div>
                            </div>
                        </div>
                    </div>
                    <!-- el end -->
                    <!-- el start -->
                    <div class="el">
                        <div class="el__overflow">
                            <div class="el__inner">
                                <div class="el__bg"></div>
                                <div class="el__preview-cont">
                                    <h2 class="el__heading">大数据</h2>
                                </div>
                                <div class="el__content">
                                    <div class="el__text">Whatever</div>
                                    <p style="color:white">
                                        
                                    </p>
                                    <div class="el__close-btn"></div>
                                </div>
                            </div>
                        </div>
                        <div class="el__index">
                            <div class="el__index-back">5</div>
                            <div class="el__index-front">
                                <div class="el__index-overlay" data-index="5">5</div>
                            </div>
                        </div>
                    </div>
                    <!-- el end -->
                </div>
            <!-- cont inner end -->
            </div>

        </div>
    </div>
</template>

<script>
export default {
    mounted() {
        // box2_style start
        var $cont = document.querySelector('.cont');
        var $elsArr = [].slice.call(document.querySelectorAll('.el'));
        var $closeBtnsArr = [].slice.call(document.querySelectorAll('.el__close-btn'));

        // setTimeout(function() {
        // $cont.classList.remove('s--inactive');
        // }, 200);

        // $elsArr.forEach(function($el) {
        // $el.addEventListener('click', function() {
        //     if (this.classList.contains('s--active')) return;
        //     $cont.classList.add('s--el-active');
        //     this.classList.add('s--active');
        // });
        // });

        // $closeBtnsArr.forEach(function($btn) {
        // $btn.addEventListener('click', function(e) {
        //     e.stopPropagation();
        //     $cont.classList.remove('s--el-active');
        //     document.querySelector('.el.s--active').classList.remove('s--active');
        // });
        // });
        //box2_style end

        $(".option").click(function () {
            $(".option").removeClass("active");
            $(this).addClass("active");
        });
    },
}
</script>

<style>
@import "@/assets/css/sy/box2_style.css";

</style>