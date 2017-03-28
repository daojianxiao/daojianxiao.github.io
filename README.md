<!DOCTYPE html>
<html lang="en">
<head>
    <meta id="viewport" name="viewport" content="width=derice-width";initial-scale="1.0";
    maximun-scale="1";user-scalable="no"; charset="UTF-8">
    <title>等比例适配布局</title>
    <style type="text/css">
        *{margin: 0;padding: 0;}
        @media (max-width: 900px) {
            html { font-size: 15px; }
        }
        @media (max-width: 400px) {
            html { font-size: 13px; }
        }
        .nav{
            width: 67.5rem;
            height: 7.8125rem;
            margin: 0 auto;
        }
        .nav-logo{
            float: left;
            margin-left: 2.8rem;
            margin-top: 0.625rem;
        }
        .logo{
            width: 5em;
            height: 5em;
        }
        .nav-item{
            float: right;
        }
        .nav-item-title{
            float: left;
            font-size: 1.6rem;
            width: 3.75rem;
            height: 1.25rem;
            margin: 3.2rem;
            color: #663300;
        }
        .ad{
            width: 67.5rem;
            height: 12.5rem;
            background: #663300;
            margin: 0 auto;
        }
        .ad-img{
            width: 7.5em;
            height: 7.5em;
            margin: 2.5em 30em;
        }
        .main{
            width:67.5rem;
            height: 100%;
            margin: 0 auto;
        }
        .main-item{
            width: 100%;
            height: 11.25rem;
            border-bottom-style: dashed;
            border-bottom-color:red;
            border-width: 0.0625rem;
        }
        .main-article{
            display: flex;
            align-items: flex-start;
        }
        .main-item-left{
            flex: 1;
            line-height:1.875em;
            font-family: 宋体;
        }
        .main-item-right{
            margin-left: 1em;
            width: 7.5em;
            height: 7.5em;
        }
        h2{
            color: #900b09;
            margin-top: 1.25em;
            margin-bottom: 1.25em;
        }
        a{
            text-decoration: none;
            color: #660000;
        }
        a:hover{
            color: #ff230d;
            display: block;
        }
        .footer{
            width: 67.5rem;
            height: 100%;
            display: flex;
            justify-content: center;
            font-weight: bold;
        }
    </style>
</head>
<body>
<div class="nav">
    <div class="nav-logo"><img class="logo" src="images/tubiao.png" ></div>
    <div class="nav-item">
        <div class="nav-item-title"><a href="#"> 博客</a></div>
        <div class="nav-item-title"><a href="#">案例</a></div>
        <div class="nav-item-title"><a href="#">关于</a></div>
    </div>
</div>
<div class="ad">
    <img class="ad-img" src="images/weixinerweima.png">
</div>
<div class="main">
    <div class="main-item"><h2><a href="#">前端工程师</a></h2>
        <div class="main-article">
    <p class="main-item-left">前端工程师的职责是制作标准优化的代码，并增加交互动态功能，
        开发JavaScript以及Flash模块，同时结合后台开发技术模拟整体效果，进行丰富互联网的Web开发，
        致力于通过技术改善用户体验。
    </p>
        <img class="main-item-right" src="images/1.jpg">
        </div>
    </div>
    <div class="main-item"><h2><a href="#">研发工程师</a></h2>
        <div class="main-article">
        <p class="main-item-left">指从事某种行业，对某种不存在的事物进行系统的研究和开发并具有一定经验的专业工作者，
            或者对已经存在的事物进行改进以达到优化目的的专业工作者。
        </p>
           <img class="main-item-right" src="images/3.jpg">
        </div>
    </div>
    <div class="main-item"><h2><a href="#">售后工程师</a></h2>
        <div class="main-article">
         <p class="main-item-left">售后技术工程师是指产品销售出去之后对客户服务的技术人员。和售前人员一样，
            售后技术工程师更懂得产品的技术性能和原理，能够解答客户的专业性问题，排除客户对于购买公司产品的疑虑，
            增强客户对公司产品优越性能的信心。
        </p>
        <img class="main-item-right" src="images/2.jpg">
        </div>
    </div>
</div>
<div class="footer">© 2017 XuanMoDing. All Rights Reserved.</div>
</body>
