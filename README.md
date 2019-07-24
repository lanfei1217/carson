<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no">
    <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
    <meta name="HandheldFriendly" content="true">
    <link rel="stylesheet" type="text/css" href="Mobile.css" />
    <link rel="stylesheet" type="text/css" href="pc.css" />

    <title>Title</title>
    <style type="text/css">
        *{margin:0;padding:0;font-family: "Helvetica Neue",Helvetica,Arial,sans-serif;color:#AAAAAA;}
        html,body{width:100%;height:100%;}
        li{list-style-type:none;}


        #resume{width:100%;margin:0 auto;width:100%;height:100%;}
        #box1{width:100%;background:red;background:url(img/7.jpg) no-repeat center;
    background-size: cover;overflow: hidden;}
    #box1 .portrait{width:100%;height:80%;position:relative;top:10%;text-align:center;}
    #box1 .portrait img{display: block;margin: 0 auto;width:100px;height:100px;border:2px solid #AAAAAA;border-radius:50%;}
    #box1 .portrait .fade{margin-top:20px;}
        #box2{width:100%;overflow: hidden;background:#CCC}
        #box2 .aboutme{text-align:center;padding:20px 0;}
        #box2 .aboutme span{border:2px solid #FFC0CB ;padding:10px;}
        #box2 .aboutdetails{padding:0 10%;}
        #box3{width:100%;}
        #box3 .skillhead{text-align:center;margin-top:20px;}
        #box3 .skillbody{padding:0 10%;}
        #box3 ul li{background:#CCC;opacity:0.3;}
        #box3 ul li .skillcolor:before{content:attr(alt);    position: relative;top: -20px;}
        #box3 ul li .skillcolor{background:cornflowerblue;width:80%;    line-height: 25px;}
        #box4{width:100%;background:green;}
        #box5{width:100%;background:black;}
        #btmNav{position:fixed;z-index:100;bottom:0;width:100%;}
        #btmNav ul{position:relative;display:table;margin:0 auto;min-width:200px;}
        #btmNav li{float:left;}

    </style>
</head>
<body>
<div id="resume">
    <div id="box1" class="boxs">
<div class="portrait">
	<img src="img/por.jpg ">
	<div class="fade fade1">Hello,Welcome in!</div>
	<div class="fade fade2">我是一名前端开发工程师</div>
</div>

    </div>
    <div id="box2" class="boxs">
	<h1 class="aboutme"><span>关于我</span></h1>
	<div class="aboutdetails"><p>我叫兰飞，湖北武汉人,是一名前端工程师。在入行之前选择前后端的时候，被前端的编程思想以及设计所吸引，毅然决然的选择了前端。</p>
	<p>之前的工作在深圳那里工作，在软通公司做华为的项目。现在回到武汉希望继续从事前端的工作，前端的技术更新换代非常快，下一个的学习目标是Anjular.js框架，
	以及node.js希望以后能够成为全栈工程师。</p></div>
    </div>
    <div id="box3" class="boxs">
	<h2 class="skillhead">专业技能</h2>
	<div class="skillbody">
		<ul>
			<li ><div alt="HTML5"  class=skillcolor>80%</div></li>
			<li ><div alt="CSS3" class=skillcolor>80%</div></li>
			<li ><div alt="JavaScript" class=skillcolor>80%</div></li>
			<li ><div alt="Vue.js" class=skillcolor>70%</div></li>
			<li ><div alt="Jquery" class=skillcolor>70%</div></li>
			<li ><div alt="Ajax" class=skillcolor>60%</div></li>
			<li ><div alt="Java" class=skillcolor>50%</div></li>
			<li ><div alt="Oracle" class=skillcolor>50%</div></li>
		</ul>
	</div>
    </div>
    <div id="box4" class="boxs">

    </div>
    <div id="box5" class="boxs">

    </div>
</div>
<div id="btmNav">
    <ul >
        <li alt="专业技能"><img src="img/icon_1.png"></li>
        <li alt="项目经验"><img src="img/icon_2.png"></li>
        <li alt="个人简介"><img src="img/icon_3.png"></li>
        <li alt="作品展示"><img src="img/icon_4.png"></li>
        <li alt="联系方式"><img src="img/icon_5.png"></li>
    </ul>
</div>

</body>
</html>
