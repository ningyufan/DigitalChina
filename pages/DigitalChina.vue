<template>
    <div class="digital_bg">
        <div class="digital_header">
            <div class="digital_bk1">
                <DigitalVideo/>
            </div>
        </div>
        <div class="digital_footer">
            <div class="digital_bk2">
            </div>
            <div class="digital_bk3"> 
            </div>
            
        </div>
    </div>
</template>

<script >
  import DigitalVideo from '../components/dchina/digital_video'
export default {
    layout:'blank',
    components:{
        DigitalVideo
    }

}
</script>

<style>
    @import "@/assets/css/digital_china.css";
</style>
