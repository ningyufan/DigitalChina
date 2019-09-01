<template>
    <div class="sy_content5">
        <div class="sycon5_t">
            5G timetable
        </div>
        <div class="sycon5_infos">
            <div class="sycon5_info" aos = "fade-up-right">
                <div>
                    China Unicom announced 5G deployment: SA will be the target architecture, focusing on eMBB in the early stage, and 5G network plan will be officially commercialized in 2020.
                </div>
                <span>2018.06.28</span>
            </div>
            <div class="sycon5_info" aos = "fade-up-left">
                <div>
                    3GPP Plenary Session (TSG#80) approved the freezing of independent networking function of 5G NR. In addition to the non-independent networking NR standard completed in December 2017, 5G has completed the first stage of full-function standardization work and entered a new stage of comprehensive industrial sprint.
                </div>
                <span>2018.06.14</span>
            </div>
            <div class="sycon5_info" aos = "fade-up-right" >
                <div>
                    The scheme of 3GPP 5G NR standard SA (Standalone, Independent Networking) was formally completed and released at the 80th TSG RAN Plenary Session of 3GPP, which marks the first truly complete international 5G standard.
                </div>
                <span>2018.06.13</span>
            </div>
            <div class="sycon5_info" aos = "fade-up-left" >
                <div>
                    The NDRC issued the Notice on Organizing and Implementing the New Generation of Information Infrastructure Construction Project in 2018, which requires that in 2018, 5G network-building pilot projects will be carried out in no less than five cities, with no less than 50 5G base stations in each city and no less than 500 5G terminals in the whole network.
                </div>
                <span>2017.12</span>
            </div>
            <div class="sycon5_info" aos = "fade-up-right">
                <div>
                    At the 78th plenary meeting of the International Telecommunication Standards Organization (ITSO) 3GPP RAN, the first version of 5G NR was officially frozen and released.
                </div>
                <span>2017.12.21</span>
            </div>
            <div class="sycon5_info" aos = "fade-up-left" >
                <div>
                    The Ministry of Industry and Information Technology of China issued a circular to formally launch the third phase of 5G technology R&amp;D test, and strive to achieve the basic objectives of the third phase test by the end of 2018.
                </div>
                <span>2017.11</span>
            </div>
            <div class="sycon5_info" aos = "fade-up-right">
                <div>
                    The Ministry of Industry and Information Technology issued the Notice on the Use of 3300-3600MHz and 4800-5000MHz Frequency Bands in the Fifth Generation Mobile Communication System, which determines 5G IF spectrum, which can meet the basic requirements of system coverage and large capacity.
                </div>
                <span>2017.11.15</span>
            </div>
            <div class="sycon5_info" aos = "fade-up-left" >
                <div>
                    The International Communications Standards Organization (ICSO) 3GPP announced the official logo of 5G.
                </div>
                <span>2017.02.09</span>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    layout:'e_content2',

}
</script>

<style>
.sycon5_t {
    height: 10vh;
    width: 100%;
    line-height: 10vh;
    font-size: 5vh;
    text-align: center;
    color: rgb(48, 189, 245);
    /* background-color: beige; */
    background-image: url(../assets/images/sy/sycon5_bgb.png);
    background-size: 100% 100%;
}
.sycon5_infos {
    height: 150vh;
    width: 100%;
    padding-top:2vh ;
    /* background-color: rebeccapurple; */
    background-image: url(../assets/images/sy/sycon5_bgb2.png);
    background-size: 100%;
    position: relative;

}
.sycon5_info {
    height: 18vh;
    width:40%;
    /* background-color: bisque; */
    background-image: url(../assets/images/sy/sycon5_bgk.png);
    /* background-repeat:no-repeat; */
    background-size: 100% 100% ;
    color: white;
}
.sycon5_info div {
    margin: 0 10px 0 10px;
}
.sycon5_infos div:nth-child(1) {
    position: absolute;
    left: 0;
    top: 2vh;
}

.sycon5_infos div:nth-child(2) {
    position: absolute;
    right: 0;
    top: 20vh;
}
.sycon5_infos div:nth-child(3) {
    position: absolute;
    left: 0;
    top: 38vh;
}
.sycon5_infos div:nth-child(4) {
    position: absolute;
    right: 0;
    top: 56vh;
}
.sycon5_infos div:nth-child(5) {
   position: absolute;
    left: 0;
    top: 74vh;
}
.sycon5_infos div:nth-child(6) {
    position: absolute;
    right: 0;
    top: 92vh;
}
.sycon5_infos div:nth-child(7) {
    position: absolute;
    left: 0;
    top: 110vh;
}
.sycon5_infos div:nth-child(8) {
    position: absolute;
    right: 0;
    top: 128vh;
}
.sycon5_infos div:nth-child(1) span,
.sycon5_infos div:nth-child(3) span,
.sycon5_infos div:nth-child(5) span,
.sycon5_infos div:nth-child(7) span{
    position: absolute;
    left: 100%;
    margin-left: 2vw;
    line-height: 18vh;
}
.sycon5_infos div:nth-child(2) span,
.sycon5_infos div:nth-child(4) span,
.sycon5_infos div:nth-child(6) span,
.sycon5_infos div:nth-child(8) span{
    position: absolute;
    right: 100%;
    margin-right: 2vw;
    line-height: 18vh;
}
</style>