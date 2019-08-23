<template>
    <div class="sy_box3">
        <div class="sybox3_t">
            数字人物
        </div>
        <div class="sybox3_con">
            <div class="options">
                <div class="option active">
                    <div class="shadow"></div>
                    <div class="label">
                        <div class="icon"> <i class="fas fa-walking"></i> </div>
                        <div class="info">
                            <div class="main">刘欣华</div>
                            <div class="sub">唐冠集团、中数信安集团董事</div>
                        </div>
                    </div>
                </div>
                <div class="option">
                    <div class="shadow"></div>
                    <div class="label">
                        <div class="icon"> <i class="fas fa-snowflake"></i> </div>
                        <div class="info">
                            <div class="main">陈思华</div>
                            <div class="sub">福建诚华信用管理有限公司董事长兼总经理</div>
                        </div>
                    </div>
                </div>
                <div class="option">
                    <div class="shadow"></div>
                    <div class="label">
                        <div class="icon"> <i class="fas fa-tree"></i> </div>
                        <div class="info">
                            <div class="main">熊立</div>
                            <div class="sub">网龙网络公司CEO</div>
                        </div>
                    </div>
                    </div>
                <div class="option">
                    <div class="shadow"></div>
                    <div class="label">
                        <div class="icon"> <i class="fas fa-tint"></i> </div>
                        <div class="info">
                            <div class="main">林拥军</div>
                            <div class="sub">易华录总经理</div>
                        </div>
                    </div>
                </div>
                <div class="option">
                    <div class="shadow"></div>
                    <div class="label">
                        <div class="icon"> <i class="fas fa-sun"></i> </div>
                        <div class="info">
                            <div class="main">熊群力</div>
                            <div class="sub">中国电子科技集团有限公司董事长、党组书记</div>
                        </div>
                    </div>
                </div>
                <div class="option">
                    <div class="shadow"></div>
                    <div class="label">
                        <div class="icon"> <i class="fas fa-sun"></i> </div>
                        <div class="info">
                            <div class="main">张桂平</div>
                            <div class="sub">苏宁环球集团董事长 </div>
                        </div>
                    </div>
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
/* sybox3手风琴效果 start */
.options {
  display: flex;
  flex-direction: row;
  align-items: stretch;
  overflow: hidden;
  min-width: 600px;
  max-width: 900px;
  width: calc(100% - 100px);
  height: 400px;
margin:60px auto;
}

@media screen and (max-width: 718px) {
  .options {
      min-width: 520px;
  }

  .options .option:nth-child(5) {
      display: none;
  }
}

@media screen and (max-width: 638px) {
  .options {
      min-width: 440px;
  }

  .options .option:nth-child(4) {
      display: none;
  }
}

@media screen and (max-width: 558px) {
  .options {
      min-width: 360px;
  }

  .options .option:nth-child(3) {
      display: none;
  }
}

@media screen and (max-width: 478px) {
  .options {
      min-width: 580px;
  }

  .options .option:nth-child(2) {
      display: none;
  }
}

.options .option {
  position: relative;
  overflow: hidden;
  min-width: 60px;
  margin: 10px;
  background: var(--optionBackground, var(--defaultBackground, #E6E9ED));
  background-size: auto 120%;
  background-position: center;
  cursor: pointer;
  transition: 0.5s cubic-bezier(0.05, 0.61, 0.41, 0.95);
}

.options .option:nth-child(1) {
  --defaultBackground: #ED5565;
  background-image: url(../../assets/images/sy/sybox3_pic1.jpg);
  
}

.options .option:nth-child(2) {
  --defaultBackground: #FC6E51;
  background-image: url(../../assets/images/sy/sybox3_pic2.jpg);

}

.options .option:nth-child(3) {
  --defaultBackground: #FFCE54;
  background-image: url(../../assets/images/sy/sybox3_pic3.jpg);

}

.options .option:nth-child(4) {
  --defaultBackground: #2ECC71;
  background-image: url(../../assets/images/sy/sybox3_pic4.jpg);
}

.options .option:nth-child(5) {
  --defaultBackground: #5D9CEC;
   background-image: url(../../assets/images/sy/sybox3_pic5.jpg);
}

.options .option:nth-child(6) {
  --defaultBackground: #AC92EC;
  background-image: url(../../assets/images/sy/sybox3_pic6.jpg);
}

.options .option.active {
  flex-grow: 10000;
  -webkit-transform: scale(1);
  transform: scale(1);
  max-width: 800px;
  margin: 0px;
  border-radius: 40px;
  background-size: auto 100%;
  /*&:active {
   transform:scale(0.9);
}*/
}

.options .option.active .shadow {
  box-shadow: inset 0 -120px 120px -120px black, inset 0 -120px 120px -100px black;
}

.options .option.active .label {
  bottom: 20px;
  left: 20px;
}

.options .option.active .label .info>div {
  left: 0px;
  opacity: 1;
}

.options .option:not(.active) {
  flex-grow: 1;
  border-radius: 30px;
}

.options .option:not(.active) .shadow {
  bottom: -40px;
  box-shadow: inset 0 -120px 0px -120px black, inset 0 -120px 0px -100px black;
}

.options .option:not(.active) .label {
  bottom: 10px;
  left: 10px;
}

.options .option:not(.active) .label .info>div {
  left: 20px;
  opacity: 0;
}

.options .option .shadow {
  position: absolute;
  bottom: 0px;
  left: 0px;
  right: 0px;
  height: 120px;
  transition: 0.5s cubic-bezier(0.05, 0.61, 0.41, 0.95);
}

.options .option .label {
  display: flex;
  position: absolute;
  right: 0px;
  height: 40px;
  transition: 0.5s cubic-bezier(0.05, 0.61, 0.41, 0.95);
}

.options .option .label .icon {
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  min-width: 40px;
  max-width: 40px;
  height: 40px;
  border-radius: 100%;
  background-color: white;
  color: var(--defaultBackground);
}

.options .option .label .info {
  display: flex;
  flex-direction: column;
  justify-content: center;
  margin-left: 10px;
  color: white;
  white-space: pre;
}

.options .option .label .info>div {
  position: relative;
  transition: 0.5s cubic-bezier(0.05, 0.61, 0.41, 0.95), opacity 0.5s ease-out;
}

.options .option .label .info .main {
  font-weight: bold;
  font-size: 1.2rem;
}

.options .option .label .info .sub {
  transition-delay: .1s;
}
/* sybox3手风琴效果 end */

</style>