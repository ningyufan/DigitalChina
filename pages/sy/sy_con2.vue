<template>
    <div class="sy_con1">
        hdfksjfhhksjh
    </div>
</template>

<script>
export default {
    layout:'content',
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
            duration: 2000,
            delay:1000
        });
    }
}
</script>

<style>

</style>