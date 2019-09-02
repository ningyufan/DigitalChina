<template>
    <div class="sy_box2">
        <div class="sybox2_t">
            Digital Dynamics
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
                                <h2 class="el__heading">Fuzhou</h2>
                            </div>
                            <div class="el__content">
                                <div class="el__text">Fuzhou: Digital China Construction Achievement Exhibition is very popular</div>
                                <p style="color:white">
                                        The exhibition is divided into four major exhibition areas: Digital Fujian Pavilion, E-government Pavilion, Digital Economy Pavilion and Digital Social Experience Pavilion.
                                        At the same time, we have arranged a new product, new technology and new application release booth for leading enterprises of digital economy. It is worth mentioning that,
                                        There are many experience items in the pavilion, so the audience can feel the convenience of life brought by the latest technology.
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
                                    <div class="el__text">5G Promotes the Interconnection of All Things</div>
                                    <p style="color:white">
                                            5G has the ability that previous generations of network technology can not achieve, 5G can let the network transcend the interconnection between people.
                                            Let billions of things interconnect and operate the machine in real time and reliably.
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
                                    <h2 class="el__heading">UAV</h2>
                                </div>
                                <div class="el__content">
                                    <div class="el__text">Third Generation Distribution Robot Exhibited in Jingdong</div>
                                    <p style="color:white">
                                            Jingdong demonstrated the Y3 UAV and tilt-rotor UAV. The tilt-rotor UAV is 3.42 meters long, 1.13 meters high and 3.78 meters wingspan, almost three times the size of the Y3 UAV.
                                            This robot is not only cute in appearance, but also powerful in function. It is based on the core technology of automatic driving. It has eight cargo hold of different sizes. It can navigate automatically according to the established route.
                                            It can deliver goods in batches in order centralized places such as universities, office buildings and residential areas under urban environment. Excellent flexibility and convenient use process will greatly improve the efficiency of distribution.
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
                                    <h2 class="el__heading">Artificial intelligence</h2>
                                </div>
                                <div class="el__content">
                                    <div class="el__text">Artificial Intelligence Reshaping Robot Industry</div>
                                    <p style="color:white">
                                            Artificial intelligence and the new generation of information technology are reshaping the robotics industry, expanding technology and application, expanding supply and demand.
                                            So the robot industry is still an important driving force to promote the transformation of new and old kinetic energy and the development of high-quality economy.
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
                                    <h2 class="el__heading">Big data</h2>
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

        setTimeout(function() {
        $cont.classList.remove('s--inactive');
        }, 200);

        $elsArr.forEach(function($el) {
        $el.addEventListener('click', function() {
            if (this.classList.contains('s--active')) return;
            $cont.classList.add('s--el-active');
            this.classList.add('s--active');
        });
        });

        $closeBtnsArr.forEach(function($btn) {
        $btn.addEventListener('click', function(e) {
            e.stopPropagation();
            $cont.classList.remove('s--el-active');
            document.querySelector('.el.s--active').classList.remove('s--active');
        });
        });
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