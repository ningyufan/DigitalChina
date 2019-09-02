<template>
        <div class="e_yl_header">
            <el-carousel :interval="5000" arrow="always" height="60vh">
                <el-carousel-item v-for="(item,idx) in items" :key="idx">
                    <el-row>
                    <el-col class="left_col_yl">
                        <div class="detail_yl">
                            <div class="titleheader_yl"><a :href="item.href">{{item.title}}</a></div>
                            <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;{{ item.p }}</p>
                            <hr class="hr_yl" />
                                <div aos="zoom-in">
                                    <a :href="item.href" style="font-size:2.5vh; font-family: STXingkai;">View content>></a>
                                </div>
                        </div>   
                    </el-col>
                    <el-col class="right_col_yl">
                        <a :href="item.href"><img :src="item.img_src" class="" height="90%" width="90%" style=" border-radius: 50vh"></a>
                    </el-col>
                </el-row>
                </el-carousel-item>
            </el-carousel>
        </div>
    </template>
    
    <script>
    export default {
        data(){
            return{
                items: [{
                    id:0,
                    title:'Intelligent City Construction',
                    href:'#e_box_cs',
                    img_src: require('../../assets/images/yulin/city_p3.png'),
                    p:'Intelligent city construction is to use information and communication technology to sense, analyze and integrate the key information of the core system of urban operation, so as to respond intelligently to various needs including people\'s livelihood, environmental protection, public safety, urban services, industrial and commercial activities. Its essence is to make use of advanced information technology to realize intelligent management and operation of the city, thus creating a better life for the people in the city and promoting the harmonious and sustainable growth of the city.',
                },{
                    id:1,
                    title:'Internet + "government services"',
                    href:'#e_box_zw',
                    img_src: require('../../assets/images/yulin/zw_p1.jpg'),
                    p:'Internet + government service "is to make use of Internet technology to restructure and reengineer realistic government services, so as to make it conform to the idea of" Internet + ", and on the basis of this, replace the offline" serial "stream with online" parallel "data flow to achieve efficient and high quality supply of government services. Taking the power of decentralization, innovation supervision and upgrading services as the core, based on the list of government power and supported by information technology.',
                    
                },{
                    id:2,
                    title:'Construction of Intelligent Tourism',
                    href:'#e_box_ly',
                    img_src: require('../../assets/images/yulin/travel_p5.png'),
                    p:'Intelligent tourism relies on information technology to actively obtain tourists\'information, form a system of data accumulation and analysis of tourists, comprehensively understand the changes of tourists\' needs, opinions and suggestions, and related information of tourism enterprises, and realize scientific decision-making and scientific management. Yulin City proposes to take tourism industry as the dominant industry, through the optimization and promotion of regional economic and social resources, especially tourism resources, related industries, ecological environment.'
                    
                },{
                    id:3,
                    title:'Big Data Helps Accurate Poverty Alleviation',
                    href:'#e_box_fp',
                    img_src: require('../../assets/images/yulin/fp_p3.jpg'),
                    p:'Comprehensive use of large data means, improve the construction of large data platform for precise poverty alleviation, dynamically manage precise poverty alleviation fund projects, ensure the effective and precise connection between poverty alleviation fund projects and poverty alleviation targets, achieve precise dynamic poverty alleviation management in the whole process of tracking, and promote the convergence, integration and application of information resources in various fields of precise poverty alleviation. In order to achieve precise monitoring of poverty alleviation.',
         
                },{
                    id:4,
                    title:'Big Data Supports Characteristic Industries',
                    href:'#e_box_cy',
                    img_src: require('../../assets/images/yulin/chanye_p4.jpg'),
                    p:'Detailed and in-depth development plans have been formulated from the aspects of domestic and foreign big data development background, local current situation and foundation, development path and strategy, infrastructure construction, industry application, industrial innovation and industrial ecology building. Yulin Municipal Government gives a detailed description of the development model, business model and related major projects of the big data industry, which fully embodies the new industrial development model of "combining planning with planning, inheritance with innovation".',
                    
                }]
            }
        }
        
    
    }
    </script>
    
    <style>
    .left_col_yl{
        width: 70%;
        height: 60vh;
        float: left;
      
      }
    .right_col_yl {
        width: 30%;
        height: 40vh;
        float: right;
        margin-top: 5vh;
        /* border: 1px solid red; */
        margin-top: 10vh;
        filter: brightness(60%);
       
      }
    .detail_yl {
        margin: 10vh 8vw;
      }
    /* .detail_yl .title_yl{
        font-size: 4vh;
        margin: 2vh auto;
        text-align: center;
    } */
    .detail_yl p{
    font-size: 3vh;
    text-align: justify;
    color:rgb(51, 135, 214);
    font-family: STXingkai;
    }
    .hr_yl {
    margin: 3vh 0 3vh 0;
    height:1px;
    border:none;
    border-top:1px solid #6ec1e2;
    }
    .detail_yl div {
        text-align: center;
    }
    .titleheader_yl{
        text-align: center;
        font-size:4vh;
        margin: 2vh auto;
        font-family: STXingkai;
    }
    </style>
    
    