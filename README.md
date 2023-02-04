# lilingWolf
web前端practice
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>网页复原1.0</title>
    
</head>
<style>
    body {
        background-color: white;
    }

    #top {
        height: 100px;
        background-color: black;
        border-color: black;
        border-style: solid;
        border-width: 1px;
        display: flex;
    }

    #box {
        cursor: pointer;
        position: relative;
        margin-left: 8%;
        float: left;
        align-self: center;
    }

    #box1 {
        width: 0;
        border-left: 26px solid transparent;
        border-right: 26px solid transparent;
        border-bottom: 15px solid blue;
    }

    #box2 {
        width: 52px;
        height: 30px;
        background-color: blue;
        font-size: 28px;
        text-align: center;
        color: black;
    }

    #box3 {
        width: 0;
        border-top: 15px solid blue;
        border-left: 26px solid transparent;
        border-right: 26px solid transparent;
    }

    #top span {
        cursor: pointer;
        align-self: center;
        position: relative;
        margin-left: 20px;
        color: white;
        font-size: 30px;
    }

    #top span:hover {
        color: deepskyblue;
    }

    #theme {
        color: darkgrey;
        font-size: 50px;
        font-family: Calibri;
        margin-left: 8%;
    }

    #item {
        color: darkgrey;
        font-size: 20px;
        margin-left: 30%;
    }

    #search {
        position: relative;
    }

   /* #right {
        height: 500px;
        width: 150px;
        background-color: aliceblue;
        border-color: gainsboro;
        border: 2px;
        border-style: solid;
        right: 3%;
        margin-top: 10px;
        position: fixed;
    }*/

    .first, .second, .third, .forth, .fifth, .sixth, .seventh {
        position: relative;
        left: 8%;
        width: 76%;
    }

    .one {
        width: 20%;
        cursor: pointer;
        position: absolute;
        left: 0;
        font-size: 20px;
        font-weight: 600;
        color: cornflowerblue;
    }

    .two {
        width: 20%;
        cursor: pointer;
        position: absolute;
        left: 37.5%;
        font-size: 20px;
        font-weight: 600;
        color: cornflowerblue;
    }

    .three {
        width: 20%;
        cursor: pointer;
        position: relative;
        left: 75%;
        font-size: 20px;
        font-weight: 600;
        color: cornflowerblue;
    }

    .one:hover, .two:hover, .three:hover {
        color: skyblue;
    }

    .yi, .er, .san {
        all: initial;
        width: 20%;
        font-size: 15px;
        color: darkgrey;
    }

    .si, .wu, .liu {
        all: initial;
        cursor: pointer;
        width: 20%;
        font-size: 10px;
        color: gainsboro;
        margin-bottom: 5px;
    }

    .si:hover, .wu:hover, .liu:hover {
        color: deepskyblue;
    }

    div {
        letter-spacing: 1px;
    }

    img {
        margin-left: 8%;
        cursor: pointer;
        height: 200px;
        width: 20%;
        margin-top: 5px;
        margin-bottom: 5px;
        border-style: solid;
        border-color: gainsboro;
    }
</style>
<body>
<div id="top">
    <div id="box">
        <div id="box1"></div>
        <div id="box2">H</div>
        <div id="box3"></div>
    </div>
    <span>Docs</span>
    <span>API</span>
    <span>News</span>
    <span>Plugins</span>
    <span>Themes</span>
    <span>About</span>
</div>
<div id="right"></div>
<p id="search"><span id="theme">Themes</span><span id="item"> 375 items</span>
    <input style="margin-left:10px;height: 35px;width: 30%" id="themeName" placeholder="Search"></p>
<div id="first">
    <img src="images/xiayan.png" alt="">
    <img src="images/xiayan2.png" alt="">
    <img src="images/xiayan3.png" alt="">
</div>
<div class="first">
    <span class="one">Xiayan1<br><span class="yi">Suitable for products blog<br><span class="si">#bootstrap&nbsp;#tag_plugins</span></span></span>
    <span class="two">Xiayan2<br><span class="er">A minimal theme<br><span class="wu">#elegant #minimal</span></span></span>
    <span class="three">Xiayan3<br><span class="san">A simple hexo theme bassed on Anatote<br><span class="liu">#clean #simple</span></span></span>
</div>
<div id="second">
    <img src="images/xiayan4.png" alt="">
    <img src="images/xiayan5.png" alt="">
    <img src="images/xiayan6.png" alt="">
</div>
<div class="second">
    <span class="one">Xiayan4<br><span class="yi">A concise theme<br><span class="si">#Vue&nbsp;#Chinese&nbsp;#dark_mode</span></span></span>
    <span class="two">Xiayan5<br><span class="yi">A brand new default theme<br><span class="wu">#official&nbsp;#widget</span></span></span>
    <span class="three">Xiayan6<br><span class="yi">SPA,flat and clean theme<br><span class="liu">#esponsive&nbsp;#中文</span></span></span>
</div>
<div id="third">
    <img src="images/zuoran1.png" alt="">
    <img src="images/zuoran2.png" alt="">
    <img src="images/zuoran3.png" alt="">
</div>
<div class="third">
    <span class="one">Zuoran1<br><span class="yi">Ocean<br><span class="si">#blue&nbsp;#picture</span></span></span>
    <span class="two">Zuoran2<br><span class="yi">Animals families<br><span class="si">#Animals&nbsp;#respnsive</span></span></span>
    <span class="three">Zuoran3<br><span class="yi">Summer theme<br><span class="si">#sun&nbsp;#summer</span></span></span>
</div>
<div id="forth">
    <img src="images/zuoran4.png" alt="">
    <img src="images/zuoran5.png" alt="">
    <img src="images/zuoran6.png" alt="">
</div>
<div class="forth">
    <span class="one">Zuoran4<br><span class="yi">Cabon is a simple theme using pjax for elegant loading<br><span
            class="si">#简约&nbsp;#Chinese&nbsp;#simple</span></span></span>
    <span class="two">Zuoran5<br><span class="yi">A Simple and Fast Theme for Hexo<br><span class="si">#Vue&nbsp;#via&nbsp;#dark_mode</span></span></span>
    <span class="three">Zuoran6<br><span class="yi">A concise theme<br><span class="si">#English&nbsp;#Chinese&nbsp;#concise</span></span></span>
</div>
<div id="fifth">
    <img src="images/bq1.png" alt="">
    <img src="images/bq2.png" alt="">
    <img src="images/bq3.png" alt="">
</div>
<div class="fifth">
    <span class="one">Baiqi1<br><span class="yi">A cool,simple & beautiful theme<br><span class="si">#respnsive&nbsp;#Chinese&nbsp;#dark</span></span></span>
    <span class="two">Baiqi2<br><span class="yi">Simple blog theme<br><span class="si">#Vue&nbsp;#Chinese&nbsp;#dark_mode</span></span></span>
    <span class="three">Baiqi3<br><span class="yi">I hope I can maintain for a long time<br><span class="si">#English&nbsp;#sky&nbsp;#dark_mode</span></span></span>
</div>
<div id="sixth">
    <img src="images/bq4.png" alt="">
    <img src="images/bq5.png" alt="">
    <img src="images/bq6.png" alt="">
</div>
<div class="sixth">
    <span class="one">Baiqi4<br><span class="yi">A simple theme based on theme landscape<br><span class="si">#Vue&nbsp;#Chinese&nbsp;#dark_mode</span></span></span>
    <span class="two">Baiqi5<br><span class="yi">particle<br><span class="si">#Vue&nbsp;#Chinese&nbsp;#dark_mode</span></span></span>
    <span class="three">Baiqi6<br><span class="yi">particle<br><span class="si">#Vue&nbsp;#Chinese&nbsp;#dark_mode</span></span></span>
</div>
<div id="seventh">
    <img src="images/bq7.png" alt="">
    <img src="images/bq8.png" alt="">
    <img src="images/bq9.png" alt="">
</div>
<div class="seventh">
    <span class="one">Baiqi7<br><span class="yi">A wonderful,elegant and eye-protected light theme for Hexo<br><span class="si">#Vue&nbsp;#Chinese&nbsp;#dark_mode</span></span></span>
    <span class="two">Baiqi8<br><span class="yi">Next is an elegant and powerful theme<br><span class="si">#light&nbsp;#Chinese&nbsp;#clean</span></span></span>
    <span class="three">Baiqi9<br><span class="yi">A light,paper-like theme<br><span class="si">#white&nbsp;#blog&nbsp;#writinf</span></span></span>
</div>
<script>
    let bbox = document.getElementById('box')
    bbox.onmouseover = function () {
    }

</script>
</body>
</html>
