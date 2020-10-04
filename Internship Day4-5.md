# school-schedule
target: finish all levels (level1-3)

##Day4

<!DOCTYPE html>
<html>
     <head> 
         <title>school schedule 2020/10</title>
         <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.12.1/css/all.min.css">
         <style>
                body {
                width: 2000px;
                height: 1500px;
                background-image: url("blue.jpg");
                background-attachment: fixed;
               }
                div {
                 color:rgb(10, 119, 228);
               }
               .table {
                 align: 1;
                 text-align: center;
                 border: 1;
                 text-align: center;
                 color: rgba(0, 2, 1, 0.842);
               }       
               .a {
                  color: pink;
               } 
               .b {
                  color:orange;
               }
               .c{
                  color:rgb(240, 47, 230);
               }
               .d{
                  color:lightcoral;
               }
               .e{
                  color:rgb(137, 192, 247);
               }
               .f{
                  color:rgb(73, 212, 247);
               }
               .g{
                  color:mediumvioletred;
               }
               .h{
                  color:rgb(226, 226, 27);
               }
               .i{
                  color:rgb(167, 235, 33);
               }
                *{
                  font-size:18px;
               }
                p{
                  text-align: center;
                  font-size: 23px;
               }
                thead{
                  text-decoration: underline;
                  font-size: larger;
               }
                *{
                 margin: 5;
                 padding: 5;
                 text-decoration: none; 
                 font-family: 'Microsoft YaHei', Arial, Helvetica, sans-serif;
               }
                 header{
                    height: 75px;
                    background: #bfb9f0;
               }
                .hust-logo{
                  max-width: 1000px;
                  padding: 0 5px;
                  margin-left: 10px;
                  margin-right: 50px;
                  border-style: hidden;
               } 
                .menu{
                   float: left;
                   display: flex;
                   align-items: center;
                   min-height: 90px;
                   position: fixed;
                   width: 100%;
                   max-width: 400px;
                   background: #6393e7;
                   top: 90px;
                   right: 0;
                   border-style:ridge;
                   padding: 20px 40px;
                   box-sizing: border-box;
               }
               .menu a:hover{
                  background: rgba(255, 255, 255, 0.842);
                  color: #436da7;
                  transform: scale(1.1);
               }
               .menu i{
                  margin-right: 7px;
                  font-size: 15px;
               }
               .menu-button{
                  float: right;
                  height: 80px;
                  line-height: 80px !important;
                  color: rgba(255, 255, 255, 0.815);
                  font-size: 26px;
                  display: none;
                  cursor: pointer;
               }
               .menu.active{
                   display: block;
               }
               .menu a{
                   display: inline-block; 
                   margin: 9px 0;
               }

               .logo{
                  float: left;
                  padding: 25px 0;
               }
               img{
                  height: 70px;
               }
               .account{
                   color: red;
               }
               .info{
                   color:indianred;
               }
               .aboutus{
                   color:rgb(236, 236, 22);
               }
               .suggestions{
                   color:rgb(17, 236, 152);
               }
              

               .menu a{
                    margin-left: 15px;
                    color: rgb(250, 241, 241); 
                    font-weight: bold;
                    font-size: 20px;
                    padding: 12px 18px;
                    border-radius: 4px;
                    transition: .4s linear;
                }

            
               }
               .navigation-menu::before{
                  content: "";
                  border-left: 10px solid lightskyblue;
                  border-right: 10px solid transparent;
                  border-bottom: 10px solid #172b4d;
                  position: absolute;
                  top: -10px;
                  right: 10px;
               }
               

         </style>
         <script>
             var lessons = prompt('您好，请您输入您所就读的院系:');
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
                 <i class="menu-button fa fa-bars" aria-hidden="true"></i>
                 <nav class="menu">
                     <a href="#"><i class="fas fa-address-book account"></i>我的帐号</a>
                     <a href="#"><i class="fas fa-calendar info"></i>资料中心</a>
                     <a href="#"><i class="fas fa-university aboutus"></i>关于我们</a>
                     <a href="#"><i class="fas fa-thumbs-up suggestions"></i>意见与评价</a>
                         
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
                         <td class="a">C语言程序设计 (计算机类一)2004-2006 西十二楼N504 卢萍</td>
                         <td></td>
                         <td></td>
                         <td class="b">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 金海</td>
                         <td></td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010 西十二楼N112 邱小霞</td>
                         <td></td>
                        
                     </tr>
                     <tr>
                         <td><b>09:00-09:50</b></td>
                         <td class="a">C语言程序设计 (计算机类一)2004-2006 西十二楼N504 卢萍</td>
                         <td class="e">新生实践课 (计算机类一)2004-2006 南一楼803-1 陈加忠</td>
                         <td></td>
                         <td class="b">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 金海</td>
                         <td></td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010 西十二楼N112 邱小霞</td>
                         <td></td>
                        
                     </tr>
                     
                     <tr>
                         <td><b>10:10-11:00</b></td>
                         <td></td>
                         <td class="e">新生实践课 (计算机类一)2004-2006 南一楼803-1 陈加忠</td>
                         <td class="f">计算思维 (计算机类一)2004-2006 西十二楼N404 李玉华</td>
                         <td class="b">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 金海</td>
                         <td class="h">线性代数（计算机类一)2006-2010 西十二楼N109 谢松法</td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010 西十二楼N112 邱小霞</td>
                         <td></td>
                         

                     </tr>
                     <tr>
                         <td><b>11:10-12:00</b></td>
                         <td></td>
                         <td></td>
                         <td class="f">计算思维 (计算机类一)2004-2006 西十二楼N404 李玉华</td>
                         <td class="b">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 金海</td>
                         <td class="h">线性代数（计算机类一)2006-2010 西十二楼N109 谢松法</td>
                         <td></td>
                         <td class="f">计算思维 (计算机类一)2004-2006 西十二楼N404 李玉华</td>
                         
                     </tr>
                     <tr>
                         <td><b>13:30-14:20</b></td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010 西十二楼N112 邱小霞</td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td class="h">中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</td>
                         <td></td>
                         <td class="f">计算思维 (计算机类一)2004-2006 西十二楼N404 李玉华</td>
                         
                     </tr>
                     <tr>
                         <td><b>14:30-15:20</b></td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010 西十二楼N112 邱小霞</td>
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
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010 西十二楼N112 邱小霞</td>
                         <td class="h">中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</td>
                         <td></td>
                         <td class="c">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 李瑞轩</td>
                         
                     </tr>
                     <tr>
                         <td><b>16:40-17:30</b></td>
                         <td></td>
                         <td></td>
                         <td class="h">中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010 西十二楼N112 邱小霞</td>
                         <td class="g">C语言程序设计实验（计算机类一)2006 南一楼804-3 李平 </td>
                         <td class="c">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 李瑞轩</td>
                         <td></td>
                         
                     </tr>
                     <tr>
                         <td><b>18:30-19:20</b></td>
                         <td class="f">计算思维 (计算机类一)2004-2006 西十二楼N404 李玉华</td>
                         <td></td>
                         <td class="h">中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</td>
                         <td></td>
                         <td></td>
                         <td class="g">C语言程序设计实验（计算机类一)2006 南一楼804-3 李平 </td>
                         <td></td>
                         
                     </tr>
                     <tr>
                         <td><b>20:10-20:50</b></td>
                         <td class="f">计算思维 (计算机类一)2004-2006 西十二楼N404 李玉华</td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td class="g">C语言程序设计实验（计算机类一)2006 南一楼804-3 李平 </td>
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

<!DOCTYPE html>
<html>
     <head> 
         <title>school schedule 2020/10</title>
         <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.12.1/css/all.min.css">
         <style>
             body {
              width: 2000px;
              height: 1500px;
              background-image: url("blue.jpg");
              background-attachment: fixed;
             }
             div {
                 color:rgb(10, 119, 228);
             }
             .table {
                 align: 1;
                 text-align: center;
                 border: 1;
                 text-align: center;
                 color: rgba(0, 2, 1, 0.842);
              }       
              .a {
                  color: pink;
              } 
              .b {
                  color:orange;
              }
              .c{
                  color:rgb(240, 47, 230);
              }
              .d{
                  color:lightcoral;
              }
              .e{
                  color:rgb(137, 192, 247);
              }
              .f{
                  color:rgb(73, 212, 247);
              }
              .g{
                  color:mediumvioletred;
              }
              .h{
                  color:rgb(226, 226, 27);
              }
              .i{
                  color:rgb(167, 235, 33);
              }
              *{
                  font-size:18px;
              }
              p{
                  text-align: center;
                  font-size: 23px;
              }
              thead{
                  text-decoration: underline;
                  font-size: larger;
             }
              *{
                 margin: 5;
                 padding: 5;
                 text-decoration: none; 
                 font-family: 'Microsoft YaHei', Arial, Helvetica, sans-serif;
             }
               header{
                    height: 75px;
                    background: #bfb9f0;
             }
               .hust-logo{
                  max-width: 1000px;
                  padding: 0 5px;
                  margin-left: 10px;
                  margin-right: 50px;
                  border-style: hidden;
             } 
               .menu{
                   float: left;
                   display: flex;
                   align-items: center;
                   min-height: 90px;
                   position: fixed;
                   width: 100%;
                   max-width: 400px;
                   background: #6393e7;
                   top: 90px;
                   right: 0;
                   border-style:ridge;
                   padding: 20px 40px;
                   box-sizing: border-box;
               }
               .menu a:hover{
                  background: rgba(255, 255, 255, 0.842);
                  color: #436da7;
                  transform: scale(1.1);
               }
               .menu i{
                  margin-right: 7px;
                  font-size: 15px;
               }
               .menu-button{
                  float: right;
                  height: 80px;
                  line-height: 80px !important;
                  color: rgba(255, 255, 255, 0.815);
                  font-size: 26px;
                  display: none;
                  cursor: pointer;
               }
                .menu.active{
                   display: block;
               }
               .menu a{
                   display: inline-block; 
                   margin: 9px 0;
               }

               .logo{
                  float: left;
                  padding: 25px 0;
               }
               img{
                  height: 70px;
               }
               .account{
                   color: red;
               }
               .info{
                   color:indianred;
               }
               .aboutus{
                   color:rgb(236, 236, 22);
               }
               .suggestions{
                   color:rgb(17, 236, 152);
               }
              

               .menu a{
                    margin-left: 15px;
                    color: rgb(250, 241, 241); /* 颜色 */
                    font-weight: bold;
                    font-size: 20px; /* 字号 */
                    padding: 12px 18px;
                    border-radius: 4px; /* 圆角 */
                    transition: .4s linear; /* 过渡时间 */
                }

            
               }
               .navigation-menu::before{
                  content: "";
                  border-left: 10px solid lightskyblue;
                  border-right: 10px solid transparent;
                  border-bottom: 10px solid #172b4d;
                  position: absolute;
                  top: -10px;
                  right: 10px;
               }
               

         </style>
         <script>
             var lessons = prompt('您好，请您输入您所就读的院系:');
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
                 <i class="menu-button fa fa-bars" aria-hidden="true"></i>
                 <nav class="menu">
                     <a href="#"><i class="fas fa-address-book account"></i>我的帐号</a>
                     <a href="#"><i class="fas fa-calendar info"></i>资料中心</a>
                     <a href="#"><i class="fas fa-university aboutus"></i>关于我们</a>
                     <a href="#"><i class="fas fa-thumbs-up suggestions"></i>意见与评价</a>
                         
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
                         <td class="a">C语言程序设计 (计算机类一)2004-2006 西十二楼N504 卢萍</td>
                         <td></td>
                         <td></td>
                         <td class="b">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 金海</td>
                         <td></td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010 西十二楼N112 邱小霞</td>
                         <td></td>
                        
                     </tr>
                     <tr>
                         <td><b>09:00-09:50</b></td>
                         <td class="a">C语言程序设计 (计算机类一)2004-2006 西十二楼N504 卢萍</td>
                         <td class="e">新生实践课 (计算机类一)2004-2006 南一楼803-1 陈加忠</td>
                         <td></td>
                         <td class="b">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 金海</td>
                         <td></td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010 西十二楼N112 邱小霞</td>
                         <td></td>
                        
                     </tr>
                     
                     <tr>
                         <td><b>10:10-11:00</b></td>
                         <td></td>
                         <td class="e">新生实践课 (计算机类一)2004-2006 南一楼803-1 陈加忠</td>
                         <td class="f">计算思维 (计算机类一)2004-2006 西十二楼N404 李玉华</td>
                         <td class="b">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 金海</td>
                         <td class="h">线性代数（计算机类一)2006-2010 西十二楼N109 谢松法</td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010 西十二楼N112 邱小霞</td>
                         <td></td>
                         

                     </tr>
                     <tr>
                         <td><b>11:10-12:00</b></td>
                         <td></td>
                         <td></td>
                         <td class="f">计算思维 (计算机类一)2004-2006 西十二楼N404 李玉华</td>
                         <td class="b">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 金海</td>
                         <td class="h">线性代数（计算机类一)2006-2010 西十二楼N109 谢松法</td>
                         <td></td>
                         <td class="f">计算思维 (计算机类一)2004-2006 西十二楼N404 李玉华</td>
                         
                     </tr>
                     <tr>
                         <td><b>13:30-14:20</b></td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010 西十二楼N112 邱小霞</td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td class="h">中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</td>
                         <td></td>
                         <td class="f">计算思维 (计算机类一)2004-2006 西十二楼N404 李玉华</td>
                         
                     </tr>
                     <tr>
                         <td><b>14:30-15:20</b></td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010 西十二楼N112 邱小霞</td>
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
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010 西十二楼N112 邱小霞</td>
                         <td class="h">中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</td>
                         <td></td>
                         <td class="c">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 李瑞轩</td>
                         
                     </tr>
                     <tr>
                         <td><b>16:40-17:30</b></td>
                         <td></td>
                         <td></td>
                         <td class="h">中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</td>
                         <td class="d">微积分（一）（上）（计算机类一)2006-2010 西十二楼N112 邱小霞</td>
                         <td class="g">C语言程序设计实验（计算机类一)2006 南一楼804-3 李平 </td>
                         <td class="c">信息计术导论（IT中国）（计算机类（一）2006-2010、计算机本硕博2001班、计卓2001班） 一号报告厅 李瑞轩</td>
                         <td></td>
                         
                     </tr>
                     <tr>
                         <td><b>18:30-19:20</b></td>
                         <td class="f">计算思维 (计算机类一)2004-2006 西十二楼N404 李玉华</td>
                         <td></td>
                         <td class="h">中国语文（能卓2001班、计算机类（一）2006-2010）西十二楼S112  张庆冰</td>
                         <td></td>
                         <td></td>
                         <td class="g">C语言程序设计实验（计算机类一)2006 南一楼804-3 李平 </td>
                         <td></td>
                         
                     </tr>
                     <tr>
                         <td><b>20:10-20:50</b></td>
                         <td class="f">计算思维 (计算机类一)2004-2006 西十二楼N404 李玉华</td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td></td>
                         <td class="g">C语言程序设计实验（计算机类一)2006 南一楼804-3 李平 </td>
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
###
