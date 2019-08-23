<template>
    <div class="sy_box4">
        <div class="sybox4_t">
            box4
        </div>
        <div class='accordion'>
            <ul>
                <li>
                    <div class="li_title"><a href="#">Keep Smile. First</a></div>
                    <a href="#"><img src='@/assets/images/sy/1.jpg'></a>
                </li>
                <li>
                    <div class="li_title">
                        <a href="#">Keep Smile. First</a></div>
                    <a href="#"><img src='@/assets/images/sy/1.jpg'></a>
                </li>
                <li>
                    <div class="li_title"><a href="#">Keep Smile. First</a></div>
                    <a href="#"><img src='@/assets/images/sy/1.jpg'></a>
                </li>
                <li>
                    <div class="li_title"><a href="#">Keep Smile. First</a></div>
                    <a href="#"><img src='@/assets/images/sy/1.jpg'></a>
                </li>
                <li>
                    <div class="li_title"><a href="#">Keep Smile. First</a></div>
                    <a href="#"><img src='@/assets/images/sy/1.jpg'></a>
                </li>
            </ul>
        </div>
    </div>
</template>


<script>
    export default {
    }
</script>

<style>
.accordion{
    width:80vw;
    height:80vh;
    overflow:hidden;
    margin:0 auto;
    box-shadow:0 0 10px 2px rgba(0,0,0,0.4);
}
.accordion ul{
    width:80vw;
}
.accordion li{
    display:block;
    width:20%;
    height:100%;
    overflow:hidden;
    position:relative;
    float:left;
    border-left:1px solid #aaa;
    box-shadow:0 0 25px 10px rgba(0,0,0,0.4);
	-webkit-transition:all .5s;
	-moz-transition:all .5s;
	-ms-transition:all .5s;
	-o-transition:all .5s;
	transition:all .5s;
}
.accordion li img{
    display:block;
}
.accordion ul:hover li{
    width:5vw;
}
.accordion ul li:hover{
    width:60vw;
}
.accordion ul li .li_title{
    width:40vw;
    height: 10vh;
    /* position: absolute;
    left: 0;
    bottom: 0; */
    background-color:rgba(0,0,0,0.5);
}
.accordion .li_title a{
    display:block;
    color:#fff;
    font-size:16px;
    padding:20px;
}
</style>