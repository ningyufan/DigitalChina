<template>
        <div class="yl_header">    
        <el-carousel :interval="5000" arrow="never" height="55vh">
            <el-carousel-item v-for="item in 5" :key="item">
            <h3>{{ item }}</h3>
            </el-carousel-item>
        </el-carousel>
    </div>
    <!-- <div class="content3"> -->
		<!-- <div class="ct3_t"><h3><span>道路</span> · 助力乡村振兴</h3></div> -->
		<!-- <div class="ct3_tp" >
			<div class="ct3a"></div>
			<div class="ct3b"></div>
			<div class="ct3c">disanye</div>
		</div>
    
    
		<div class="ct3a_f" >
			<span class="ct3a_span">航拍广西大石山区扶贫路</span>
			<p  class="ct3a_p1">近年来，广西加大对贫困地区道路基础设施的建设力度，加快“最后一公里”——屯级路的建设，为大石山区群众的脱贫致富和加快推进广西脱贫攻坚工作奠定基础。</p>
			<p  class="ct3a_p2">这是广西大化瑶族自治县七百弄乡弄合村的屯级公路</p>

			<span class="ct3b_span">航拍广西龙胜盘山公路</span>
			<p class="ct3b_p1">近年来，广西桂林龙胜各族自治县将农村公路建设与脱贫攻坚、乡村振兴紧密结合，通过实施“农村公路建设大会战”，积极推进农村公路建设。截至目前，龙胜119个行政村全部实现水泥（沥青）公路全覆盖，方便了农村群众出行，助推了精准扶贫工作。</p>
			<p class="ct3b_p2">图为5月3日航拍的龙胜镇日新村的盘山公路。</p>

			<span class="ct3c_span">“飞阅”广西农村路</span>
			<p class="ct3c_p1">进入“十三五”以来，广西农村公路建设不断加快。“十三五”期间，广西计划大力实施农村交通和交通扶贫工程，着力实现所有建制村通沥青（水泥）路，分类推进已有公路改造和建制村间道路连通，基本形成以县道为骨架、乡道为支线、村道为脉络的农村公路网络体系，解决农村“出行难”问题，提高交通扶贫精准化水平。</p>
			<p class="ct3c_p2">在广西都安瑶族自治县龙湾乡加范村，一名村民骑行在回家的路上</p>
		</div>

		<div class="ct3_bt">
			<div class="ct3_bt1"><span>a</span></div>
			<div class="ct3_bt2"><span>b</span></div>
		</div>
		<div class="ct3_num">
			<span class="ct3a_num">01</span>
			<span class="ct3b_num">02</span>
			<span class="ct3c_num">03</span>
			<span class="ct3_num2">/3</span>
		</div>
	</div> -->

    </template>
    
    <script>
        export default{
	// 		head:{
	// 			link: [
	// 			{ rel: 'stylesheet', href: 'css/animate.css'},
	// 			{ rel: 'stylesheet', href: 'css/iziModal.css'},
	// 			{ rel: 'stylesheet', href: 'css/common.css'},
    //             { rel: 'stylesheet', href: 'css/liu.css'},
    //         ]
	// 	},
    }


	// var example1=new sHover("example0","intro0");
/*new WOW().init();*/


// $("#modal-default").iziModal({
//           title: "Welcome to the iziModal",
//           subtitle: "Simple, complete and lightweight modal plugin with jquery.",
//           iconClass: 'icon-announcement',
//           width: 700,
//           padding: 20
//       });
//       $(document).on('click', '.trigger-default', function (event) {
//           event.preventDefault();
//           $('#modal-default').iziModal('open');
//       });


//       $("#modal-iframe").iziModal({
//           title: 'iziModal with iframe',
//           subtitle: 'Lorem ipsum dolor sit amet, consectetur adipisicing elit.',
//           iconClass: 'icon-settings_system_daydream',
//           transitionIn: 'transitionIn',
//           transitionOut: 'transitionOut',
//           headerColor: '#fff',
//           theme: 'light',
//           width: 1200,
//           overlayClose: true,
//           iframe : true
//       });


//       $(document).on('click', '.trigger-iframe', function (event) {
//           event.preventDefault();
          //$('#modal-iframe').trigger('http://210.36.247.156/t183/izi.open', this);
    //       $("#modal-iframe").iziModal('open', event);
    //   });


    //   $("#modal-custom").iziModal({
    //       overlayClose: false,
    //       width: 600,
    //       autoOpen: false,
    //       overlayColor: 'rgba(0, 0, 0, 0.6)',
    //       onOpened: function() {
    //           console.log('onOpened');
    //       },
    //       onClosed: function() {
    //           console.log('onClosed');  
    //       }
    //   });
    //   $(document).on('click', '.trigger-custom', function (event) {
    //       event.preventDefault();
    //       $('#modal-custom').iziModal('open');
    //   });

    //   $("#modal-alert").iziModal({
    //       title: "Your message has been sent successfully",
    //       iconClass: 'icon-check',
    //       headerColor: '#5bbd72',
    //       width: 600
    //   });
    //   $(document).on('click', '.trigger-alert', function (event) {
    //       event.preventDefault();
    //       $('#modal-alert').iziModal('open');
    //   });

    //   $("#modal-alert2").iziModal({
    //       title: "Attention",
    //       subtitle: 'you are being disconnected..',
    //       iconClass: 'icon-power_settings_new',
    //       headerColor: '#BD5B5B',
    //       width: 600
    //   });
    //   $(document).on('click', '.trigger-alert2', function (event) {
    //       event.preventDefault();
    //       $('#modal-alert2').iziModal('open');
    //   });

    //   $("#modal-large").iziModal({
    //       title: "成绩单",
    //       subtitle: "",
    //       iconClass: 'icon-chat',
    //       overlayColor: 'rgba(255, 255, 255, 0.4)',
    //       headerColor: '#334c7b',
    //       iconColor: '#00ffba',
    //       width: 700,
    //       padding: 20
    //   });
    //   $(document).on('click', '.trigger-large', function (event) {
    //       event.preventDefault();
    //       $('#modal-large').iziModal('open');
    //   });



    //   $(document).on('opening', '#modal-iframe', function (e) {
          //console.dir(e);
    //   });
    //   $(document).on('opened', '#modal-iframe', function (e) {
          //console.dir(e);
    //   });
    //   $(document).on('closing', '#modal-iframe', function (e) {
          //console.dir(e);
    //   });
    //   $(document).on('closed', '#modal-iframe', function (e) {
          //console.dir(e);
    //   });


    //   $("#modal-custom").on('click', 'header a', function(event) {
    //       event.preventDefault();
    //       var index = $(this).index();
    //       $(this).addClass('active').siblings('a').removeClass('active');
    //       $(this).parents("div").find("section").eq(index).removeClass('hide').siblings('section').addClass('hide');

    //       if( $(this).index() === 0 ){
    //           $("#modal-custom .iziModal-content .icon-close").css('background', '#ddd');
    //       } else {
    //           $("#modal-custom .iziModal-content .icon-close").attr('style', '');
    //       }
    //   });

    //   $("#modal-custom").on('click', '.submit', function(event) {
    //       event.preventDefault();

    //       var fx = "wobble",  //wobble shake
    //           $modal = $(this).closest('.iziModal');

    //       if( !$modal.hasClass(fx) ){
    //           $modal.addClass(fx);
    //           setTimeout(function(){
    //               $modal.removeClass(fx);
    //           }, 1500);
    //       }
    //   });

    </script>
    
    <style>
        .yl_header{
            margin-top:5vh;
            margin-left: 5%;
            margin-right: 5%;

        }
    </style>