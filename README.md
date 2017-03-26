<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>flex布局</title>
    <style type="text/css">
        *{margin:0; padding:0;}
        .by{
            display: flex;
            justify-content:center;
        }
        .header {
            width: 1080px;
            height: 125px;
            background: #FFFF99;
            display: flex;
            justify-content: space-between;
        }
        .logo{
            width:87px;
            height:80px;
            margin-left:100px;
            margin-top: 26px;
            margin-bottom: 10px;
        }
        .nav{
            font-size: 20px;
            display: flex;
            align-items: center;
            margin-top:45px;
        }
        a{
            text-decoration: none;
            color: #660000;
        }
        a:hover{
           color: #ff230d;
            display: block;
        }
        .nav-item{
            width: 110px;
            height:65px;
            margin-right: 26px;
        }
        .ad{
            display: flex;
            justify-content:center;
        }
        .main{
            display: flex;
            justify-content:center;
        }
        .main-left{
            width: 820px;
            height: 100%;
            margin-top: 15px;
            margin-right: 10px;
        }
        .main-right{
            width: 240px;
            margin-left: 10px;
            margin-top: 15px;
        }
        p{
            line-height: 30px;
            font-family: 宋体;
        }
        h1{
            color: #663300;
            margin: 15px 5px;
        }
        h2{
            color: #663300;
            margin-top: 5px;
            margin-bottom: 15px;
        }
        .main-left-title{
            margin-top: 15px;
            margin-bottom: 15px ;
        }
        .module-title{
            margin-top: 15px;
            margin-bottom: 15px ;
            width: 820px;
            float: left;
            height: 132px;;
        }
        .main-right-ad{
            margin: 15px 10px;
        }
        .article-item-title{
            margin-bottom: 15px;
        }
        .footer{
            display: flex;
            justify-content: center;
            height: 100%;
            margin-top: 50px;
            margin-bottom: 35px;
            font-weight: bold;
        }
        .article{
            display: flex;
            align-items: flex-start;
        }
        .article-item{
           flex: 1;
        }
        .imgs{
            margin-left: 1em;
            width: 120px;
            height: 120px;
        }
    </style>
</head>
<body>
<div class="by">
  <div class="header">
    <div ><img class="logo" src="images/tubiao.png" > </div>
    <div class="nav">
       <div class="nav-item"><a href="#">主页</a></div>
       <div class="nav-item"><a href="#">往期</a></div>
       <div class="nav-item"><a href="#">博客</a></div>
       <div class="nav-item"><a href="#">关于</a></div>
    </div>
  </div>
</div>
<div class="ad">
   <a href="#"> <img src="images/datu.jpeg" width="1080px" height="420px"></a>
</div>
<div class="main">
    <div class="main-left">
        <div class="main-left-title"><h1><a href="#"> 热门影视>></a></h1><p class="article-item-title">“人类的天职总是巧妙的创造各种机会，让人们在实现历史
            目标的过程中，培养自己的能力与胆识。” <br>“构成一生中的每一天，都应该是庄严的。” </p><hr></div>
        <div class="main-left-article">
           <div class="module-title"> <h2><a href="#"> 速度与激情7</a></h2>
               <div class="article"> <p class="article-item">
            故事开始于多米尼克和布莱恩各自的小队成员带着赦免令回到美国的一年之后。他们过着循规蹈矩的日子，家乡生活的感觉很好。
            然而他们都不知道，危险正在悄然接近，冷血的英国特勤杀手肖出现了。从东京的韩被残忍谋杀，到洛杉矶霍布斯的死里逃生......
           </p>
             <a href="#"> <img class="imgs" src="images/1.jpg" ></a>
               </div>
           </div>
            <div class="module-title"><h2><a href="#">寒战</a></h2>
                <div class="article"><p class="article-item">
            作为亚洲金融中心的香港被称作“最安全的城市”，岂料警局接到一通匿名电话，对方声称劫持了警队的一辆前线冲锋车以及车内
            的五名警员和武器装备。此次事件引起了香港警队高层的高度重视，适逢处长（王敏德 饰）出访国外，此时由鹰派人物......</p>
                    <a href="#" ><img class="imgs"  src="images/2.jpg" ></a>
                </div>
           </div>
            <div class="module-title"><h2><a href="#">金刚狼3</a></h2>
                <div class="article"><p class="article-item">
            故事发生在2029年，彼时，X战警早已经解散，作为为数不多的仅存的变种人，金刚狼罗根（休·杰克曼 Hugh Jackman 饰）和卡
            利班（斯戴芬·莫昌特 Stephen Merchant 饰）照顾着年迈的X教授（帕特里克·斯图尔特 Patrick Stewart 饰）......</p>
               <a href="#"> <img class="imgs" src="images/6.jpg" ></a>
               </div>
            </div>
        </div>
    </div>
    <div class="main-right">
        <div class="main-right-ad"><p>英国伦敦市中心议会大厦附近22日下午发生恐怖袭击事件，造成包括1名警察和1名
            恐怖分子在内的4人死亡，另有20多人受伤。</p></div>
        <div class="main-right-ad"><p>事业单位选派符合条件的专业技术人员到企业挂职或者参与项目合作，是强化科技
            同经济对接、创新成果同产业对接、创新项目同现实生产力对接的重要举措。</p></div>
        <div class="main-right-ad"><p>在神华集团以分红的名义大量抽走中国神华资金的情况下，一旦中国神华有什么看好的项目需要投资，那么中
            国神华就只能向二级市场的投资者伸手要钱，哪怕是向特定对象定增，最终买单的还是二级市场的投资者。</p></div>
    </div>
</div>
<div class="footer">© 2017 XuanMoDing. All Rights Reserved.</div>
</body>
</html>
