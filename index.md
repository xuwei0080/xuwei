<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style type="text/css">

        #main-top{
            width: 100%;
            height: 150px;
        }
        #main-left{
            width:15%;
            height: 950px;
            float: left;
            /* background-color: yellow; */
        }
        #main-right{
            width: 25%;
            height: 950px;
            float: left;
            text-align: center;
            /* background-color: aquamarine;  */
        }
        #main-middle
        {
            float:left;
            width: 60%;
            height: 950px;
             /* background-color: antiquewhite; */
        }
        #main-footer
        {
            width: 100%;
            clear:both;/*清除左右浮动*/
            margin-top:20px;
            position:relative;/*避免底部留白*/
            height: auto;
        }
        body
        {
            background-image: url(back.png);
        }
        #topnav{
            width: 100%;
            overflow: hidden;
            background-color: white;
            border: 1px solid black;
            border-radius: 10px;
            opacity: 0.4;
            text-align: center;
        }
        #footer{
                width: 100%;
                overflow: hidden;
            border-radius: 10px;
            text-align: center; 
        }
        a{
            font-size: 40px;
            color: black;
            text-decoration: none;
        }
        .afooter
        {
            font-size: 30px;
            color:teal  ;
            font-weight: bold;
            text-decoration: none;
        }   
        h1{
            font-size: 60px;    
            text-align: center;
        }
        ul{
            background-color: white;
            padding-left: 70px;
            opacity: 0.4;
            text-align: left;
            font-size:40px ;
            text-shadow: 0px 3px 5px rgba(9, 21, 61, 0.5);
            list-style-type: none;
            border: 1px solid white;
            border-radius: 10px;
        }
        .a-left{
            font-size: 35px ;   
            
        }
        #photo{
            height: 50px;
            width: 50px;
        }
        #photo1{
            height: 300px;
            width: 300px;
            opacity: 0.9;
            border-radius: 20px;
        }
        .li-k{
            font-size: 30px;
            text-align: center;
        }
        .left-ul
        {
            background-color: white;
            padding-left: 70px;
            opacity: 0.4;
            font-size:40px ;
            width: auto;
            text-shadow: 0px 3px 5px rgba(9, 21, 61, 0.5);
            list-style-type: none;
            border: 1px solid white;
            border-radius: 10px;
        }
        .left-ul1
        {
            background-color: white;
            padding-left: 70px;
            opacity: 0.4;
            font-size:30px ;
            width: auto;
            text-shadow: 0px 3px 5px rgba(9, 21, 61, 0.5);
            list-style-type: none;
            border: 1px solid white;
            border-radius: 10px;
        }
        textarea{
            opacity: 0.4;
        }
             
      </style>
</head>

<body>
    <div id="main-top">
        <h1>欢迎你，O_O似曾相识</h1>
        <div id="topnav">
      <a href="Four(1).html">    博客园    </a>
      <a href="https://www.cnblogs.com/jyt604743080/p/15468200.html">    首页    </a>
      <a href="https://www.cnblogs.com/jyt604743080/p/15536266.html">    新随笔    </a>
      <a href="">    联系    </a>
      <a href="Four(3).html" target="mainframe">    介绍    </a>
      <a href="https://www.cnblogs.com/jyt604743080/p/15536266.html">    管理    </a>
      </div>
    </div>
     <div id="main-left">

              <ul>
                  <li> </li>
                  <li> </li>
                  <li><img  id="photo" src="assets\images\php\image\皮卡丘.png"><a class="a-left" href="https://www.cnblogs.com/jyt604743080/p/15969981.html">闪存</a><img  id="photo" src="assets\images\php\image\皮卡丘.png"></li>
                  <li> </li>
                  <li><img  id="photo" src="assets\images\php\image\皮卡丘1.png"><a class="a-left" href="https://www.cnblogs.com/jyt604743080/p/15969981.html">博客</a><img  id="photo" src="assets\images\php\image\皮卡丘1.png"></li> 
                  <li> </li>
                  <li><img  id="photo" src="assets\images\php\image\皮卡丘2.png"><a class="a-left" href="https://www.cnblogs.com/jyt604743080/p/15969981.html">小组</a><img  id="photo" src="assets\images\php\image\皮卡丘2.png"></li>
                  <li> </li>
                  <li><img  id="photo" src="assets\images\php\image\皮卡丘3.png"><a class="a-left" href="https://www.cnblogs.com/jyt604743080/p/15969981.html">新闻</a><img  id="photo" src="assets\images\php\image\皮卡丘3.png"></li>
                  <li> </li>
                  <li><img  id="photo" src="assets\images\php\image\皮卡丘1.png"><a class="a-left" href="https://www.cnblogs.com/jyt604743080/p/15969981.html">博问</a><img  id="photo" src="assets\images\php\image\皮卡丘1.png"></li>
                  <li> </li>
                  <li><img  id="photo" src="assets\images\php\image\皮卡丘4.png"><a class="a-left" href="https://www.cnblogs.com/jyt604743080/p/15970013.html">收藏</a><img  id="photo" src="assets\images\php\image\皮卡丘4.png"></li>
                  <li> </li>
                  <li><img  id="photo" src="assets\images\php\image\皮卡丘.png"><a class="a-left" href="https://www.cnblogs.com/jyt604743080/p/15970013.html">文库</a><img  id="photo" src="assets\images\php\image\皮卡丘.png"></li>
                    <li> </li>
                    <li> </li>
                </ul>

     </div>
     <div id="main-middle">
            <iframe name="mainframe" src="Four(2).html" frameborder="0"width="1500"height="920" ></iframe>
     </div>
      <div id="main-right">
          <br>
          <br>
          <br>
            <div  class="left-ul">
               <li class="li-k">公告</li>
               <li class="li-k"> <a href="https://www.cnblogs.com/jyt604743080/">昵称： O_O似曾相识</a></li>
               <li class="li-k"> <a href="https://www.cnblogs.com/jyt604743080/p/15969981.html"></a>园龄： 8个月</li>
                 <li class="li-k"><a href="https://www.cnblogs.com/jyt604743080/p/15969981.html"></a>粉丝： 5</li>
               <li class="li-k"> <a href="https://www.cnblogs.com/jyt604743080/p/15969981.html"></a>关注： 6</li>
             </div> 
          <br>
             <div>
            <div  class="left-ul1">
                <li class="li-k">阅读排行榜</li>
                <li > <a class="li-k" href="https://www.cnblogs.com/jyt604743080/p/15468200.html">1. 数据库的增删改查(122)</a></li>
                <li > <a class="li-k" href="https://www.cnblogs.com/jyt604743080/p/15969981.html"> 2. 河北省重大技术需求征集系统原型(106)</a></li>
                <li ><a class="li-k" href="https://www.cnblogs.com/jyt604743080/p/15531228.html"> 3. 阿里编程规范(94)</a></li>
                <li> <a class="li-k"href="https://www.cnblogs.com/jyt604743080/p/15536266.html">  4. 图书管理系统（关于数据库的增删改查）(81)</a></li>
                <li > <a class="li-k"href="https://www.cnblogs.com/jyt604743080/p/15768920.html">  5. IDEA 配置安卓(Android)开发环境(70)</a></li>
              </div>  
          </div>
             <br>
             <br>
             <h1 style="color: aliceblue; opacity: 0.5;">
                 记得留言那:
             </h1>
        <div>
         <textarea name="" id="" cols="70" rows="10"></textarea>
         </div>
        </div>
     
        </div>
       <div id="main-footer">
        <div id="footer">
                <a href="https://www.cnblogs.com/jyt604743080/p/15468200.html" class="afooter">   关于我们      </a>
                <a href="https://www.cnblogs.com/jyt604743080/p/15966422.html" class="afooter">   联系我们      </a>
                <a href="https://www.cnblogs.com/jyt604743080/p/15966422.html" class="afooter">   使用条款      </a>
                <a href="https://www.cnblogs.com/jyt604743080/p/15966422.html" class="afooter">   意见反馈      </a>
            </div>
       </div>
</body>
</html>
