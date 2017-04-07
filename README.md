# cheng
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">


    <script type="text/javascript" src="jQuery-1.7.1.js"></script>
    <script type="text/javascript" src="test.js"></script>
    <script type="text/javascript" src="selectpic.js"></script>
    <title>Title</title>
</head>
<body style="background-image: url(img/background.jpg);background-repeat: no-repeat;background-attachment:fixed;background-size:100% 100%;">
  <div align="center">
      <img style="width:auto;height:80px;margin-top:20px" src="img/logo.png"/>
  </div>

 <div align="center"  ;>
  <form  id="bdfm" target="_blank" name="bdfm" method="get" action="http://www.baidu.com/s">
    <table align="center"width="600px">
        <tr>

            <td id="inputpic"><br/><input  style="width: 600px;height: 32px;border:none;" type="text" id="search1" name="word"  /></td>
            <td><br/><img style="width: 40px;height: 30px; cursor:pointer;position: relative;right:50px;top:3px"  src="img/img_search.png" id="search" onclick="pic()" /></td>

            <td><br/><button style="width: 100px; height: 38px ;position: relative;right:50px;cursor:pointer" type="submit"  >开始搜索 </button></td>
        </tr>
    </table>
  </form>
</div>


 <div id="startsearch"></div>
<div id="selectpic" ></div>

</body>
</html>
