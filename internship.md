# school-schedule
Target: finish all levels (level1-3) go foward to success !

Day1

<!DOCTYPE html>
<html>
     <head>
         <title>school schedule 2020/10/2</title>
         <style>
          body {
             width: 2000px;
             height: 1500px;
             background-image: url("blue.jpg");
             }
         </style>
     </head>
     <body>
         <p>第八周 共十一节课</p>
         <div>08:00-08:50</div>
         <span>C语言程序设计 (计算机类一)2004-2006 西十二楼N504 卢萍</span>
         <span></span>
         <span>微积分（一）（上）（计算机类一)2006-2010 西十二楼N112 邱小霞</span>
         <span></span>
         <span></span> 
         <span></span>
         <span>综合英语 （一）（计算机类一)2006 西五楼407 阙紫江</span> 
         <span></span>
         <span>新生实践课 (计算机类一)2004-2006 南一楼803-1 陈加忠</span>
         <span></span>
         <span></span>
         <span></span>
         <span>中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</span>
         <span></span>
         <span>啊</span>
         <span></span>
         <span>计算思维 (计算机类一)2004-2006 西十二楼N404 李玉华</span>
         <span></span>
         <span>信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 金海 </span>
         <span></span>
         <span></span>
         <span>中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</span>
         <span></span>
         <span>线性代数（计算机类一)2006-2010 西十二楼N109 谢松法</span>
         <span></span>
         <span>中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112 王毅</span>
         <span></span>
         <span>C语言程序设计实验（计算机类一)2006 南一楼804-3 李平 </span>
         <span></span>
         <span></span>
         <span></span>
         <span>信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 李瑞轩</span>
         <span></span>
         <span></span>
         <div>09:00-09:50</div>
         <div>10:10-11:00</div>
         <div>11:10-12:00</div>
         <div>13:30-14:20</div>
         <div>14:30-15:20</div>
         <div>15:40-16:30</div>
         <div>16:40-17:30</div>
         <div>18:30-19:20</div>
         <div>20:10-20:50</div>
         <div>21:00-21:50</div>>
         
         <span></span>
         <span></span>
         <span></span>
    </body>
<html>

##小金子的编程之旅ww
###第一项项目-课表
####～第一章～
1.遇到的问题()
*之前在网上课程看觉得挺容易上手的，没想到万事开头难，原以为直接打代码在vscode里就行，原来还要装上插件才可執行(可以预览当时所打的代码结果显示在网页上)，可安了半天也不行
*不知道怎么改文件的名字+不能预览网页
*不能预览所放置图片
*突然不能预览网页
-
2.解决方法(百度后找学姐询问+上网/百度寻找解决方法+自己嘗试)
*安装插件:open in browser(这才对的)，並不是我原本插的vscode.browser 
*按f12/在文件夹里的文件上修名字+文件名字后缀是.html，差没有.html.txt的.txt，所以要把它给删掉
*原来vscode本身的文件要与所想要加入的图片，要在同一文件自录之下
*发现原来打错/打漏代码，比如少了闭合，没有.和英文的引号之类的等等,之后要多注意，多练习

3.学会了什么
*学会了后缀是什么'如何让电脑显示后缀
*不只在vscode行码，也要安装插件辅助自己
*vscode文件和自己想引入的图片，应放在同一文件目录
*多留意自己所打的代码，防止小错误的发生！
*时常保存文件
*保存好文件，再刷新，才可预览图片～


Day 2

<!DOCTYPE html>
<html>
     <head> 
         <link rel="stylesheet" href="style proj.css" />
         <title>school schedule 2020/10</title>
         <style>
             body{
              width:2000px;
              height:1500px;
              background-image:url("blue.jpg");
              background-attachment:fixed;
}
        
             .menu li{
              color:rosybrown;
              font-weight:bold;
              font-size:large;
}
             .table{
                 align:1;
                 text-align:center;
                 border:1;
                 text-align:center;
                 color:rgba(0,2,1,0.842);
}
              .a{
                  color:pink;
}
              .b{
                  color:orange;
}
              .c{
                  color:rgb(240,47,230);
}
              .d{
                  color:lightcoral;
}
              .e{
                  color:rgb(137,192,247);
}
              .f{
                  color:rgb(73,212,247);
}
              .g{
                  color:mediumvioletred;
}
              .h{
                  color:rgb(226,226,27);
}
              .i{
                  color:rgb(167,235,33);
}
              *{
                  font-size:18px;
}
              p{
                  text-align:center;
                  font-size:23px;
}
              thead{
                  text-decoration:underline;
}



       
         </style>
         <script>
             var lessons=prompt('您好，请您输入您所就读的院系:');
             switch(lessons){
                 case "计算机科学与技术":
                     alert("下面是您的课表");
                     break;
                 default:
                     alert("抱歉，没有此课表！只有计算机科学与技术的课表，下面即为您展示！")
}
            
         </script>

     </head>
     <body>
         <nav>
              <div class="hust">华中大计科课程表</div>
              <ul class="menu">
                  <li>我的帐号</li>
                  <li>课程表</li>
                  <li>联系我们</li>
                  <li>意见与评价</li>
              </ul>
         </nav>
        
         <p>计算机科学与技术学院 2020级课程表</p>
         <p>第八周 共三十四节课</p>
            <table class="table">
                <thead>
                    <tr> 
                         <th></th>      
                         <th>10月1日周一</th>
                         <th>10月2日周二</th>
                         <th>10月3日周三</th>
                         <th>10月4日周四</th>
                         <th>10月5日周五</th>
                         <th>10月6日周六</th>
                         <th>10月7日周日</th> 
                    </tr>
                </thead>
                <tbody>
                    <tr>
                         <td><b>08:00-08:50</b></td>
                         <td class="a">C语言程序设计 (计算机类一)2004-2006西十二楼N504 卢萍</td>
                         <td></td>
                         <td></td>
                         <td class="b">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 金海</td>
                         <td></td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010西十二楼N112 邱小霞</td>
                         <td></td>
                       
                     </tr>
                     <tr>
                         <td><b>09:00-09:50</b></td>
                         <td class="a">C语言程序设计 (计算机类一)2004-2006西十二楼N504 卢萍</td>
                         <td class="e">新生实践课 (计算机类一)2004-2006南一楼803-1 陈加忠</td>
                         <td></td>
                         <td class="b">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 金海</td>
                         <td></td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010西十二楼N112 邱小霞</td>
                         <td></td>
                       
                     </tr>
                    
                     <tr>
                         <td><b>10:10-11:00</b></td>
                         <td></td>
                         <td class="e">新生实践课 (计算机类一)2004-2006南一楼803-1 陈加忠</td>
                         <td class="f">计算思维 (计算机类一)2004-2006西十二楼N404 李玉华</td>
                         <td class="b">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 金海</td>
                         <td class="h">线性代数（计算机类一)2006-2010西十二楼N109 谢松法</td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010西十二楼N112 邱小霞</td>
                         <td></td>
                        

                     </tr>
                     <tr>
                         <td><b>11:10-12:00</b></td>
                         <td></td>
                         <td></td>
                         <td class="f">计算思维 (计算机类一)2004-2006西十二楼N404 李玉华</td>
                         <td class="b">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 金海</td>
                         <td class="h">线性代数（计算机类一)2006-2010西十二楼N109 谢松法</td>
                         <td></td>
                         <td class="f">计算思维 (计算机类一)2004-2006西十二楼N404 李玉华</td>
                        
                     </tr>
                     <tr>
                         <td><b>13:30-14:20</b></td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010西十二楼N112 邱小霞</td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td class="h">中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</td>
                         <td></td>
                         <td class="f">计算思维 (计算机类一)2004-2006西十二楼N404 李玉华</td>
                        
                     </tr>
                     <tr>
                         <td><b>14:30-15:20</b></td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010西十二楼N112 邱小霞</td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td class="h">中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</td>
                         <td></td>
                         <td></td>
                       
                     </tr>
                     <tr>
                         <td><b>15:40-16:30</b></td>
                         <td></td>
                         <td class="i">综合英语 （一）（计算机类一)2006 西五楼407 阙紫江</td>
                         <td></td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010西十二楼N112 邱小霞</td>
                         <td class="h">中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</td>
                         <td></td>
                         <td class="c">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 李瑞轩</td>
                        
                     </tr>
                     <tr>
                         <td><b>16:40-17:30</b></td>
                         <td></td>
                         <td></td>
                         <td class="h">中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010西十二楼N112 邱小霞</td>
                         <td class="g">C语言程序设计实验（计算机类一)2006 南一楼804-3 李平</td>
                         <td class="c">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 李瑞轩</td>
                         <td></td>
                        
                     </tr>
                     <tr>
                         <td><b>18:30-19:20</b></td>
                         <td class="f">计算思维 (计算机类一)2004-2006西十二楼N404 李玉华</td>
                         <td></td>
                         <td class="h">中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</td>
                         <td></td>
                         <td></td>
                         <td class="g">C语言程序设计实验（计算机类一)2006 南一楼804-3 李平</td>
                         <td></td>
                        
                     </tr>
                     <tr>
                         <td><b>20:10-20:50</b></td>
                         <td class="f">计算思维 (计算机类一)2004-2006西十二楼N404 李玉华</td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td class="g">C语言程序设计实验（计算机类一)2006 南一楼804-3 李平</td>
                         <td></td>
                        
                     </tr>

                     <tr>
                         <td><b>21:00-21:50</b></td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td></td>
                     </tr>
                </tbody>
            </table>

     </body>
</html>

#第二章~
1.遇到的问题
*卡在了制作表格框架，不知道该使用哪个标签开头才对
*卡在了css的格式里
*不能展示预览器
*今天要上课，少了许多时间做作业(school schedule)，害怕完成不了所制定的目标
2.解决方法
*删了原本的div 和span ，使用了table建立表格结构
*重温了一下css的格式表达，然后正確地选择格式，比如类选择器写所定的名字(a):. (a)等等
*加入缺少的符号和改掉中文的符号換成英文的在!
*先去上课，把空余时间尽量挤出来，或者在有空的时间想想怎么解决当前遇到问题的打码
3.学会了什么
*了解清楚table的运用，更適合
*复习，清楚理解背后的概念，再去选择使用
*时常留意打码的每一步，避免出错
*学会时间安排，尽量去平均兩者

Day3

<!DOCTYPE html>
<html>
     <head> 
         <title>school schedule 2020/10</title>
         <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.12.1/css/all.min.css";>
         <style>
             body{
              width:2000px;
              height:1500px;
              background-image:url("blue.jpg");
              background-attachment:fixed;
}
             div{
                 color:rgb(10,119,228);
}
             .table{
                 align:1;
                 text-align:center;
                 border:1;
                 text-align:center;
                 color:rgba(0,2,1,0.842);
}
              .a{
                  color:pink;
}
              .b{
                  color:orange;
}
              .c{
                  color:rgb(240,47,230);
}
              .d{
                  color:lightcoral;
}
              .e{
                  color:rgb(137,192,247);
}
              .f{
                  color:rgb(73,212,247);
}
              .g{
                  color:mediumvioletred;
}
              .h{
                  color:rgb(226,226,27);
}
              .i{
                  color:rgb(167,235,33);
}
              *{
                  font-size:18px;
}
              p{
                  text-align:center;
                  font-size:23px;
}
              thead{
                  text-decoration:underline;
                  font-size:larger;
}


       
         </style>
         <script>
             var lessons=prompt('您好，请您输入您所就读的院系:');
             switch(lessons){
                 case "计算机科学与技术":
                     alert("下面是您的课表");
                     break;
                 default:
                     alert("抱歉，没有此课表！只有计算机科学与技术的课表，下面即为您展示！")
}
 
         </script>

     </head>
     <body>
         <header>
             <div class="hust-logo">
                 <a href="#" class="logo"><img src="hust logo.jpg" alt=""></a>
                 <i class="fa fa-bars" aria-hidden="true"></i>
                 <nav class="navigation-menu">
                     <a href="#"><i class="fas fa-address-book"></i>我的帐号</a>
                     <a href="#"><i class="fas fa-calendar"></i>资料中心</a>
                     <a href="#"><i class="fas fa-university"></i>关于我们</a>
                     <a href="#"><i class="fas fa-thumbs-up"></i>意见与评价</a>
                        
                 </nav>
             </div>
            
         </header>
        
        
         <p>计算机科学与技术学院 2020级课程表</p>
         <p>第八周 共三十四节课</p>
            <table class="table">
                <thead>
                    <tr> 
                         <th></th>      
                         <th>10月1日周一</th>
                         <th>10月2日周二</th>
                         <th>10月3日周三</th>
                         <th>10月4日周四</th>
                         <th>10月5日周五</th>
                         <th>10月6日周六</th>
                         <th>10月7日周日</th> 
                    </tr>
                </thead>
                <tbody>
                    <tr>
                         <td><b>08:00-08:50</b></td>
                         <td class="a">C语言程序设计 (计算机类一)2004-2006西十二楼N504 卢萍</td>
                         <td></td>
                         <td></td>
                         <td class="b">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 金海</td>
                         <td></td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010西十二楼N112 邱小霞</td>
                         <td></td>
                       
                     </tr>
                     <tr>
                         <td><b>09:00-09:50</b></td>
                         <td class="a">C语言程序设计 (计算机类一)2004-2006西十二楼N504 卢萍</td>
                         <td class="e">新生实践课 (计算机类一)2004-2006南一楼803-1 陈加忠</td>
                         <td></td>
                         <td class="b">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 金海</td>
                         <td></td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010西十二楼N112 邱小霞</td>
                         <td></td>
                       
                     </tr>
                    
                     <tr>
                         <td><b>10:10-11:00</b></td>
                         <td></td>
                         <td class="e">新生实践课 (计算机类一)2004-2006南一楼803-1 陈加忠</td>
                         <td class="f">计算思维 (计算机类一)2004-2006西十二楼N404 李玉华</td>
                         <td class="b">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 金海</td>
                         <td class="h">线性代数（计算机类一)2006-2010西十二楼N109 谢松法</td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010西十二楼N112 邱小霞</td>
                         <td></td>
                        

                     </tr>
                     <tr>
                         <td><b>11:10-12:00</b></td>
                         <td></td>
                         <td></td>
                         <td class="f">计算思维 (计算机类一)2004-2006西十二楼N404 李玉华</td>
                         <td class="b">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 金海</td>
                         <td class="h">线性代数（计算机类一)2006-2010西十二楼N109 谢松法</td>
                         <td></td>
                         <td class="f">计算思维 (计算机类一)2004-2006西十二楼N404 李玉华</td>
                        
                     </tr>
                     <tr>
                         <td><b>13:30-14:20</b></td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010西十二楼N112 邱小霞</td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td class="h">中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</td>
                         <td></td>
                         <td class="f">计算思维 (计算机类一)2004-2006西十二楼N404 李玉华</td>
                        
                     </tr>
                     <tr>
                         <td><b>14:30-15:20</b></td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010西十二楼N112 邱小霞</td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td class="h">中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</td>
                         <td></td>
                         <td></td>
                       
                     </tr>
                     <tr>
                         <td><b>15:40-16:30</b></td>
                         <td></td>
                         <td class="i">综合英语 （一）（计算机类一)2006 西五楼407 阙紫江</td>
                         <td></td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010西十二楼N112 邱小霞</td>
                         <td class="h">中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</td>
                         <td></td>
                         <td class="c">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 李瑞轩</td>
                        
                     </tr>
                     <tr>
                         <td><b>16:40-17:30</b></td>
                         <td></td>
                         <td></td>
                         <td class="h">中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010西十二楼N112 邱小霞</td>
                         <td class="g">C语言程序设计实验（计算机类一)2006 南一楼804-3 李平</td>
                         <td class="c">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 李瑞轩</td>
                         <td></td>
                        
                     </tr>
                     <tr>
                         <td><b>18:30-19:20</b></td>
                         <td class="f">计算思维 (计算机类一)2004-2006西十二楼N404 李玉华</td>
                         <td></td>
                         <td class="h">中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</td>
                         <td></td>
                         <td></td>
                         <td class="g">C语言程序设计实验（计算机类一)2006 南一楼804-3 李平</td>
                         <td></td>
                        
                     </tr>
                     <tr>
                         <td><b>20:10-20:50</b></td>
                         <td class="f">计算思维 (计算机类一)2004-2006西十二楼N404 李玉华</td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td class="g">C语言程序设计实验（计算机类一)2006 南一楼804-3 李平</td>
                         <td></td>
                        
                     </tr>

                     <tr>
                         <td><b>21:00-21:50</b></td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td></td>
                     </tr>
                </tbody>
            </table>

     </body>
</html>

#第三章～
1.遇见的事，学到的东西
*今天打算弄个菜单，可以点开展示更多功能的那种互动，找到了一个影片，来学学怎么做。在学习的过程中，最开心的是今天发现了一个网站font awesome，是一个可以使用图标的网站，与一般不同的是他不用把图标下载下来，丢上到文件里再引用，而是直复制他所提供的图标名称或代码，就可以使用了，非常方便！但尽管如此方便，还是遇到问题，並不能展示在预览网页中，原来是在前面加fas才会显示！
