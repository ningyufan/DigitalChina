<template>
    <div class="sy_box1">
        <div class="sybox1_t">
            数字行业
        </div>
        <div class="sybox1_con">
            <div id="wrap">
                <a href="/sy/sy_con1" class="hb">
                    <div class="c">
                        <img src="@/assets/images/sy/sybox1_pic1.jpg" alt=""/>
                        <div class="txt">
                            <h1>数字经济</h1>
                            <p>数字经济将开启2亿人口就业空间</p>
                        </div>
                    </div>
                </a>
                <div class="fullBg">
                    <img src="@/assets/images/sy/sybox1_pic1.jpg" alt=""/>
                </div>
                <a href="/sy/sy_con2" class="hb">
                    <div class="c">
                        <img src="@/assets/images/sy/sybox1_pic2.jpg" alt=""/>
                        <div class="txt">
                            <h1>数字经济</h1>
                            <p>互联网医院可医保买单了，商业保险还远吗？</p>
                        </div>
                    </div>
                </a>
                <div class="fullBg">
                    <img src="@/assets/images/sy/sybox1_pic2.jpg" alt=""/>
                </div>
                <a href="/sy/sy_con3" class="hb">
                    <div class="c">
                        <img src="@/assets/images/sy/sybox1_pic3.jpg" alt=""/>
                        <div class="txt">
                            <h1>数字教育</h1>
                            <p>“智慧AI老师”或将改变未来教育方式</p>
                        </div>
                    </div>
                </a>
                <div class="fullBg">
                    <img src="@/assets/images/sy/sybox1_pic3.jpg" alt=""/>
                </div>
                <a href="#" class="hb">
                    <div class="c">
                        <img src="@/assets/images/sy/sybox1_pic4.jpg" alt=""/>
                        <div class="txt">
                            <h1>数字教育</h1>
                            <p>互联网＋人工智能驱动在线教育产业普及</p>
                        </div>
                    </div>
                </a>
                <div class="fullBg">
                    <img src="@/assets/images/sy/sybox1_pic4.jpg" alt=""/>
                </div>
            </div>
            
        </div>
    </div>
</template>

<script>
export default {

}
</script>

<style>
.sy_box1{
  height: 100%;
  width: 100%;
  position: relative;
}
.sybox1_t {
  height: 15vh;
  width: 100vw;
  position: absolute;
  left: 0;
  top: 0;
  line-height: 15vh;
  text-align: center;
  font-size: 5vh;
  color: rgb(48, 189, 245);
}
#wrap{
  position:absolute;
  left:0; top:0;
  width:100%;
  height:100%;
  display:flex;
  align-items:stretch;
}
.hb {
  position:relative;
  width:25%;
  z-index:1;
  display:flex;
  align-items:center;
  z-index:2;
  trasnform:scale(.97);
}
.c{
  position:relative;
  display:block;
  max-width:90%;
}
.c img {
  position:relative;
  display:block;
  width:100%;
  height:auto;
  z-index:2;
}
.txt {
  position:absolute;
  top:100%; left:10%;
  width:80%;
  opacity:0;
  padding:1em 0 0 1em;
  border-left:1px solid;
  z-index:1;
  transform:scaleY(1) translateY(-50px);
  transition:transform .2s, opacity .5s;
}
h1 {
  font-size:1.2em;
  font-weight:700;
  text-transform:uppercase;
}
.hb:hover .txt {
  opacity:1;
  transform:scaleY(1) translateY(0);
}
.fullBg {
  position: inherit ;top:0;left:0;width:100%;height:100%;
  opacity:0;
  transition:transform .5s, opacity .5s;
  transform:scale(1);
  z-index:1;
}
.fullBg img {
  width:100%;height:100%;
  object-fit:cover;object-position:center;
  opacity:.5;
}
.hb:hover + .fullBg {
  opacity:0.8;
  /* transform:scale(1.02); */
  }
.credits {
  position:fixed;
  bottom:0;right:0;
  padding:1.5em;
  font-size:.8em;
  text-align:right;
  font-style:italic;
  opacity:.8;
  transition:opacity .2;
  z-index:3;
}
.credits:hover {
  text-decoration:underline;
  opacity:1;
}
</style>