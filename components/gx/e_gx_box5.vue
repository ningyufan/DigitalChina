<template>
    <div class="gx_box5">
        <div class="tab">
            Intelligence Education
        </div>
        <div class="tab_two">
            Engineering Colleges and Universities of 100 Universities in Guangxi
        </div>
        <div class="box5_con">
            <div class="con1" @click="dialog1 = true" aos = "fade-right">
                <img src="../../assets/images/gx/box6_pic1.png" height="100%" width="100%" alt="">
            </div>				
            <div class="con2" aos = "fade-left">
                <div class="tariffCards">
                    <div class="card1"  @click="dialog2 = true">
                        <img src="../../assets/images/gx/box6_pic2.png" alt="Economy">
                        <h3>Nanning Normal University</h3>						
                    </div>
                    <div class="card2" @click="dialog3 = true">
                        <img src="../../assets/images/gx/box6_pic3.png" alt="Premium Economy">
                        <h3>Guangxi Normal University of Science and Technology</h3>						
                    </div>
                    <div class="card3" @click="dialog4 = true">
                        <img src="../../assets/images/gx/box6_pic4.png" alt="Business">
                        <h3>Beibu Gulf University</h3>						
                    </div>
                    <div class="card4" @click="dialog5 = true">
                        <img src="../../assets/images/gx/box6_pic5.png" alt="First" >
                        <h3>Yulin Normal University</h3>						
                    </div>
                    <div class="card5" @click="dialog6 = true">
                        <img src="../../assets/images/gx/box6_pic6.png" alt="First">
                        <h3>Nanning Branch of Guilin University of Technology</h3>
                    </div>
                </div>
            </div>
            <el-dialog
                title="Swiss wing Education"
                :visible.sync="dialog1"
                width="60%">
                <span>
                    <video
                        autoplay loop 
                        lass="fillWidth" 
                        width="100%">
                        <source src="../../assets/video/gx_box6_video1.mp4" type="video/mp4"/>
                        浏览器不支持 video 标签，建议升级浏览器。
                        <source src="../../assets/video/gx_box6_video1.mp4" type="video/webm"/>
                        浏览器不支持 video 标签，建议升级浏览器。
                    </video>
                    <br/>
                    <p>
                        &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                        Data China's "100 Schools Project" is an innovative project of integration of industry and education implemented jointly by the School Planning and Construction Development Center of the Ministry of Education and Dawning Information Industry Co., Ltd.
                    </p><br/>
                    <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                        Starting in May 2016, the project plans to select 100 Application-oriented Undergraduate Colleges and universities nationwide in the next three years to build a total of 100 "Dawn Ruiyi Big Data College" in the mode of school-enterprise cooperation.
Hundreds of "Big Data Application Innovation Centers" and networking into "Big Data Application Collaborative Innovation Network" to create both talents training and training.
Big Data Super Platform for Scientific Research Innovation and Serving Local Economic Functions.
                    </p><br/>
                </span>
                <span slot="footer" class="dialog-footer">
                    <el-button type="primary" @click="dialog1 = false">Return</el-button>
                </span>
            </el-dialog>
            <el-dialog
                title="Nanning Normal University"
                :visible.sync="dialog2"
                width="60%">
                <span>
                    <div class="dialog_pic">
                        <img src="../../assets/images/gx/box6_pic2.png" height="100%" alt="">
                    </div>
                    <div class="dialog_info">
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            Nanning Normal University, or Nanning Normal University for short, is located in Nanning City, capital of Guangxi Zhuang Autonomous Region.
It has been selected as the second phase of the national basic capacity-building project of universities in the central and Western regions, as well as the research and practice projects of new scientific research, to serve as a model university for deepening the reform of innovation and entrepreneurship education in the whole country.
According to the Ministry of Education, the Pilot Universities of the "100-University Project" project in China, the counterpart supporting construction institutions of Southwest University, and the newly added doctoral degree awarding units in Guangxi have set up construction units.
Guangxi first-class discipline construction colleges and universities, counterpart support Guangxi Normal University for Nationalities.
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The School was founded in 1953 by the Guangxi Secondary School for Further Education College and in 1905 by the Nanning Road Normal School.
In December 2002, Guangxi Normal University merged with Guangxi Nanning Normal School for Nationalities to form a new Guangxi Normal University. In December 2018,
The school was formally renamed Nanning Normal University.
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            According to the information on the school's official website in March 2019, the school has four campuses, Mingxiu, Changgang, Wuhe and Wuming, covering an area of 3476.68 mu, and has a collection of 201.4 million books.
It co-operates an independent college with 22 teaching colleges, 6 teaching assistant units and 66 general undergraduate majors, and 1018 full-time teachers.
There are 16 690 full-time undergraduates, 1 466 postgraduates and 422 specialists.
                        </p>
                    </div>
                    
                </span>
                <span slot="footer" class="dialog-footer">
                    <el-button type="primary" @click="dialog2 = false">返回</el-button>
                </span>
            </el-dialog>
            <el-dialog
                title="Guangxi Normal University of Science and Technology"
                :visible.sync="dialog3"
                width="60%">
                <span>
                    <div class="dialog_pic">
                        <img src="../../assets/images/gx/box6_pic3.png" height="100%" alt="">
                    </div>
                    <div class="dialog_info">
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Guangxi Normal University of Science and Technology is located in Laibin City, Guangxi Zhuang Autonomous Region.
As a public undergraduate college in Guangxi Autonomous Region, it is the first pilot University in China's "100-School Project" according to the Ministry of Education.
The pilot school for the overall transformation and development of newly-built undergraduate schools in Guangxi is jointly constructed by the Guangxi Science and Technology Department and the Laibin Municipal People's Government.								
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            The college can be traced back to the Yishan Teachers College, founded in 1958, and the Liuzhou Teachers College was established on the basis of Liuzhou National Agricultural Technology School in 1970.
In 2015, it was upgraded to Guangxi Normal University of Science and Technology. In 2016, it was selected as the first pilot University of China's "100 Schools Project" project based on Ministry of Education data.
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            As of September 2017, the College covers an area of 1617.1 mu, including 1010.1 mu in Laibin Campus, 607 mu in Liuzhou Campus, and 13 secondary colleges.
Fifty-nine majors, including 16 undergraduate majors, 862 faculty members, more than 12600 full-time students, from the United States, South Korea, Thailand, etc.
There are 58 foreign students from Vietnam and other countries.
                        </p>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">
                    <el-button type="primary" @click="dialog3 = false">Return</el-button>
                </span>
            </el-dialog>
            <el-dialog
                title="Beibu Gulf University"
                :visible.sync="dialog4"
                width="60%">
                <span>
                    <div class="dialog_pic">
                        <img src="../../assets/images/gx/box6_pic4.png" height="100%" alt="">
                    </div>
                    <div class="dialog_info">
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Beibuwan University is located in Qinzhou City, Guangxi Zhuang Autonomous Region.
It is a full-time general college with engineering, science and management as its main subjects. It is the first pilot University of "100-School Project" in China, which was jointly constructed by the People's Government of Guangxi Zhuang Autonomous Region and the State Oceanic Administration.
The project units of "Applied Undergraduate Colleges" planned and constructed in the 13th Five-Year Plan of the State, and the colleges and Universities Based on the "Innovative Experiment Project of Integration of Industry and Education" of the School Planning and Construction Development Center of the Ministry of Education,
The newly-built undergraduate colleges and universities in Guangxi are experimenting with overall transformation and development, and the first batch of governing colleges and universities of the National Union of Applied Technologies Universities. The campus of the university is a 3A-level scenic spot.							
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The predecessor of the school is Qinzhou Normal School, which was founded in 1973. Qinzhou Teachers'College was established in 1982.
Qinzhou Branch of Guangxi Normal University was established in 1985. In 1988, the Qinzhou Teacher Training College was renamed Qinzhou Regional Education College, and in 1991 it was transformed into Qinzhou Teachers'College.
In 2004, Qinzhou Normal School for Nationalities (including Qinzhou Branch of Guangxi Radio and Television University), founded in 1906, was incorporated into Qinzhou Normal College. In 2006, it was upgraded to Qinzhou College.
At the end of November 2018, the Ministry of Education approved the establishment of Beibuwan University on the basis of Qinzhou College.
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            As of May 2019, the school covers an area of 2070 mu. It has 18 teaching units, 50 undergraduate majors and 3 master's degree authorization points. There are more than 1200 faculty members.
(More than 800 full-time teachers) and 14,000 full-time students.
                        </p>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">
                    <el-button type="primary" @click="dialog4 = false">Return</el-button>
                </span>
            </el-dialog>
            <el-dialog
                title="Yulin Normal University"
                :visible.sync="dialog5"
                width="60%">
                <span>
                    <div class="dialog_pic">
                        <img src="../../assets/images/gx/box6_pic5.png" height="100%" alt="">
                    </div>
                    <div class="dialog_info">
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Yulin Normal University Located in China's excellent tourist cities,
Yulin City, in southeastern Guangxi, is a full-time general undergraduate university directly under Guangxi Zhuang Autonomous Region and one of the four Pilot Universities for comprehensive reform of higher education in Guangxi.
In 2016, he was enrolled in China's "100 Schools Project" cooperative university in the Ministry of Education data.
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The predecessor of the school is the Yulin Normal School of Guangxi Province founded in 1945.
In 1952, it was renamed Yulin Normal School. In 1958, it was upgraded to Guangxi Yulin Teachers College.
In 1978, Yulin Normal College was restored with the approval of the State Council. In 1994, it was renamed Yulin Teachers College.
In 2000, with the approval of the Ministry of Education, Yulin Teachers College, Yulin Education College, Yulin Higher Vocational and Technical College,
Yulin Branch of Guangxi Radio and Television University was merged and upgraded to Yulin Normal College.
In 2015, it was designated as one of the four Pilot Universities for comprehensive reform of higher education in Guangxi.					
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;As of June 2019, the school covers an area of 1746 mu. The school has 16 secondary colleges.
It covers economics, law, pedagogy, literature, history, science, engineering, management, agriculture, art and other 10 University disciplines.
There are 63 general undergraduate majors. At present, there are 1330 faculty members, 1002 full-time teachers and 806 doctoral and master degree teachers.
The school has 18550 full-time students and nearly 1100 foreign students.
                        </p>
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">
                    <el-button type="primary" @click="dialog5 = false">Return</el-button>
                </span>
            </el-dialog>
            <el-dialog
                title="Nanning Branch of Guilin University of Technology"
                :visible.sync="dialog6"
                width="60%">
                <span>
                    <div class="dialog_pic">
                        <img src="../../assets/images/gx/box6_pic6.png" height="100%" alt="">
                    </div>
                    <div class="dialog_info">							
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            Guilin University of Technology AT Nanning
                            It is a branch of Guilin University of Technology. It mainly undertakes applied undergraduate education and specialized education.
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            In December 2017, the School Planning and Construction Development Center of the Ministry of Education organized experts to conduct a centralized audit of the declared institutions.
According to the basic principles of "university declaration, enterprise docking and scheme optimization", the expert group's opinions are comprehensively considered, and the geographical distribution is taken into account as a whole.
Finally, Nanning Branch of Guilin University of Science and Technology was selected as the fifth data University of "100-university project" construction in Guangxi.
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            The predecessor of Nanning Branch of Guilin University of Technology is Nanning Nonferrous Metals Industrial School, which was founded in 1985.
In 2000, Nanning Branch was approved by the Education Department of Guangxi Zhuang Autonomous Region to merge into Guilin University of Technology as a whole, and became an important organic part of Guilin University of Technology.
                        </p><br/>
                        <p>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
                            As of July 2018, the campus area of Nanning Anji and Airport is more than 1,300 mu, with a total construction area of over 300,000 square meters, and has six departments.
There are 19 undergraduate majors and 41 higher vocational majors. There are nearly 500 teachers and nearly 12,000 full-time students.
                        </p>							
                    </div>
                </span>
                <span slot="footer" class="dialog-footer">
                    <el-button type="primary" @click="dialog6 = false">Return</el-button>
                </span>
            </el-dialog>
        </div>
    </div>
</template>

<script>
export default {
    data() {
        return {  
			dialog1: false,
			dialog2: false,
			dialog3: false,
			dialog4: false,
			dialog5: false,
			dialog6: false,
        }
    }
}
</script>

<style>
.gx_box5 {
    width: 100vw;
    height: 100vh;
    background-image: url(../../assets/images/gx/bg6.jpg);
    background-size: 100% 100%; 
    position: relative;
}
.gx_box5 .tab {
    width: 100vw;
    height: 15vh;
    line-height: 15vh;
    text-align: center;
    font-size: 5vh;
    color: rgb(48, 189, 245);
}
.gx_box5 .tab_two {
    width: 100vw;
    height: 6vh;
    line-height: 6vh;
    text-align: center;
    font-size: 4vh;
    color: rgb(48, 189, 245);
}
.gx_box5 .tab:hover {
    animation: tab_scale 1s linear 3;
}

@keyframes tab_scale{
    33.3%{
        font-size: 5vh;
    }
    66.6%{
        font-size: 5.5vh;
    }
    99.9%{
        font-size: 5vh;
    }
}

.gx_box5 .box5_con {
    height: 70vh;
    width: 80vw;
    margin: 0 auto 0;
    position: relative;
    /* background-color:rgba(48, 189, 245, 0.6) */
}
.gx_box5 .box5_con .con1{
    height: 60vh ;
    width: 30vw;
    position: absolute;
    left: 2vw;
    top: 5vh;
    background-color: #8063E1;
    background-image: linear-gradient(135deg, #BD7BE8, #8063E1);
    box-shadow: 20px 20px 60px rgba(34, 50, 84, 0.5), 1px 1px 0px 1px #8063E1;
    border-radius: 20px;
    transform-style: preserve-3d;
    transform: perspective(800px) rotateY(30deg);
    transition: all 1s ease;
}
.gx_box5 .box5_con .con1:hover {
    transform: perspective(800px) rotateY(0deg);
    background-image: linear-gradient(60deg, rgba(255, 255, 255, 0) 20%, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0) 80%);
    transform: scale(0.8, 0.8);
}
.gx_box5 .box5_con .con1:after {
    position: absolute;
    top: -70px;
    left: 0;
    content: "";
    width: 200%;
    height: 200%;
  }
.gx_box5 .box5_con .con2{
    height: 70vh ;
    width: 45vw;
    position: absolute;
    left:35vw;
    top: 0;
}

.tariffCards {
    height: 60vh ;
    /* width: 45vw; */
    position: absolute;
    top: 50%;
    left: 50%;
    margin: -30vh 0 0 -11.2vw;
    user-select: none;
    transform: translate3d(0, 0, 0);
    transform-style: preserve-3d;
  }
  .tariffCards:after {
    position: absolute;
    bottom: -27px;
    left: 5%;
    content: "";
    width: 65%;
    height: 30px;
    border-radius: 100%;
    background-image: radial-gradient(rgba(34, 50, 84, 0.04), rgba(34, 50, 84, 0));
  }
  .tariffCards > div {
    position: relative;
    width: 22vw;
    height: 20vh;
    border-radius: 12px;
    color: white;
    transform: rotateX(45deg) rotateY(-15deg) rotate(45deg);
    transition: all 0.4s ease;
    overflow: hidden;
    /* cursor: pointer; */
  }
  .tariffCards > div:after {
    position: absolute;
    top: -70px;
    left: 0;
    content: "";
    width: 200%;
    height: 200%;
    background-image: linear-gradient(60deg, rgba(255, 255, 255, 0) 20%, rgba(255, 255, 255, 0.1), rgba(255, 255, 255, 0) 80%);
    transform: translateX(-100%);
  }
  .tariffCards > div img {
    height: 13vh;
    width: 13vh;
    margin-top: 2vh;
    margin-left: 1vw;
    pointer-events: none;
  }
  .tariffCards > div h3 {
    position: absolute;
    bottom: 2vh;
    left: 1vw;
    font-size: 18px;
    font-weight: 800;
  }

  .tariffCards > div.card1 {
    margin-top: 0;
    z-index: 4;
    background-color: #8063E1;
    background-image: linear-gradient(135deg, #BD7BE8, #8063E1);
    box-shadow: 20px 20px 60px rgba(34, 50, 84, 0.5), 1px 1px 0px 1px #8063E1;
  }
  .tariffCards > div.card2 {
    margin-top: -70px;
    z-index: 3;
    background-color: #3F58E3;
    background-image: linear-gradient(135deg, #7F94FC, #3F58E3);
    box-shadow: 20px 20px 60px rgba(34, 50, 84, 0.5), 1px 1px 0px 1px #3F58E3;
  }
  .tariffCards > div.card3 {
    margin-top: -70px;
    z-index: 2;
    background-color: #2C6FD1;
    background-image: linear-gradient(135deg, #21BBFE, #2C6FD1);
    box-shadow: 20px 20px 60px rgba(34, 50, 84, 0.5), 1px 1px 0px 1px #2C6FD1;
  }
  .tariffCards > div.card4 {
    margin-top: -70px;
    z-index: 1;
    background-color: #352F64;
    background-image: linear-gradient(135deg, #415197, #352F64);
    box-shadow: 5px 5px 60px rgba(34, 50, 84, 0.1), 1px 1px 0px 1px #352F64;
  }
  .tariffCards > div.card5 {
    margin-top: -70px;
    background-color: #352F64;
    background-image: linear-gradient(135deg, #081964, #352F64);
    box-shadow: 5px 5px 60px rgba(34, 50, 84, 0.1), 1px 1px 0px 1px #352F64;
  }
  .tariffCards > div:hover {
    transform: rotateX(30deg) rotateY(-15deg) rotate(30deg) translate(-25px, 50px);
  }
  .tariffCards > div:hover:after {
    transform: translateX(100%);
    transition: all 1.2s ease-in-out;
  }
  .gx_box5 .box5_con .dialog_pic {
      height: 30vh;
      width: 100%;
      text-align: center;
      /* background-color: #21BBFE; */
  }

</style>