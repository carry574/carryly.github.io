## Welcome to carry 疯狂乐园
```markdown
<!DOCTYPE html>

<html>



<head>

    <meta charset="UTF-8">

    <title>about me</title>

    <meta name="keywords" content="个人网站,GeeYo,ThinkPHP,bootstrap">

    <meta name="description" content="这里是周红的个人网站，记录并分享着他想记录与分享的一切，可是他有点懒，更新的并不是那么频繁！">

    <meta http-equiv="x-ua-compatible" content="ie=edge">

    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">

    <!-- Js -->

    <link rel="stylesheet" href="style/css/bootstrap.min.css">

    <script src="style/js/jquery.min.js"></script>

    <script src="style/js/tether.min.js"></script>

    <script src="style/js/bootstrap.min.js"></script>

    <link href="style/css/style.css" type="text/css" rel="stylesheet" />

</head>



<body background="related/07.jpg">

    <!-- Header -->

    <div class="nav">

        <a class="logo" href="index.html"><img src="style/images/logo.png" width="40" title="红"></a>

        <span id="site_runtime" style="color:white; font-size: xx-small;"></span>     

        <a class="logo pull-right sobtn"><span class="glyphicon glyphicon-search" style="color: #B4B4B4;"></span></a>

    </div>

    <!-- ArtBox -->

    <div class="container">

        <div class="row">

            <div class="artbox col-sm-8">

                <div class="about" style="margin-bottom: 40px;">

                    <p><span style="font-size: 18pt;">关于站主</span></p>

                    

                    <p>站主名叫周红</p>

                    <p>Java开发攻城狮</p>

                    <p>喜欢音乐、爱生活、爱折腾、爱行走</p>

                    <p></p>

                    <p>&nbsp;</p>

                    <p><span style="font-size: 18pt;">关于本站</span></p>

                    <p><span style="line-height: 1.5;">本网站定位为个人网站</span></p>

                    <p>在这里总结学习知识，记录平日所思</p>

                    <p><span style="line-height: 1.5;">徜徉于缤纷错乱的互联网世界，</span><span style="line-height: 1.5;">且歌，且行，且冥…</span></p>

                    <p>&nbsp;</p>

                    <p><span style="font-size: 18pt;">关于简历</span></p>

                    <h3> <a href="https://tom-shushu.github.io/MyWebsite.github.io/"></a></h3>

                    <input class="c1" id="btN91wang" value="点击在线访问我的简历" onClick="window.open('https://tom-shushu.github.io/MyWebsite.github.io/') "

                    	style="background-color: #5CB3FD;"

                    	 /> 

                    <p><span style="line-height: 1.5;">站主的个人简历</span></p>

                    <p>若是对我满意，请记得联系我！！</p>

                    <p>如果你觉得有需要还可以免费下载我的简历作为参考！！</p>

                    <p>「<a href="Tpl/简历.pdf" download="简历.pdf">点击下载</a>」</p>

                    <p>&nbsp;</p>

                    

                    <p><span style="font-size: 24px;">支持本站</span></p>

                    <p>有什么idea，欢迎在下面给我留言或发邮件到：<a href="http://mail.qq.com/cgi-bin/qm_share?t=qm_mailme&amp;email=1462533241@qq.com" target="_blank">1462533241@qq.com</a></p>

                </div>

            </div>

        </div>

    </div>

    <!-- Footer -->

    <div class="clear"></div>

    <div class="foot">

        

        <!-- 弹出层 -->

        <div class="so">

            <i class="iconfont" title="关闭">×</i>

            <div class="container">

                <form action="https://www.baidu.com/baidu" target="_blank">

                    <input name="tn" type="hidden" value="SE_zzsearchcode_shhzc78w">

                    <input type="text" name="word" class="form-control" baiduSug="1" value="百度搜索..." />

                    <input type="submit" style="display: none;" />

                </form>

            </div>

        </div>

    </div>

    <div class="to-top">↑</div>

    <div class="gb2-site" >

      	<a id="gb2big5" ><span>繁</span></a>

      </div>

    <script src="style/js/GeeYo.js"></script>

    <script src="style/js/gb2big5.js"></script>

    <!--

    	作者：15249239025@163.com

    	时间：2019-04-18

    	描述：时间

    -->

<script type="text/javascript">

    function show_site_runtime(){

	window.setTimeout("show_site_runtime()",1000); // 每秒运行一次函数

	X=new Date("04/10/2019 00:00:00"); //在这里修改你的建站时间

	Y=new Date();

	T=(Y.getTime()-X.getTime()); // 获取当前时间与指定时间之间的时间间隔（ms）	

	i=24*60*60*1000;

	d=T/i;

	D=Math.floor(d); // 计算天数并向下取整

	h=(d-D)*24;

	H=Math.floor(h); // 计算剩余不足一天的小时数并向下取整

	m=(h-H)*60;

	M=Math.floor(m); // 计算剩余不足一小时的分钟数并向下取整

	s=(m-M)*60;

	S=Math.floor(s); // 计算剩余不足一分钟的秒数并向下取整

	site_runtime.innerHTML="现在是："+ Y+ "<br>" +"网站已平稳运行："+D + " 天 " + H + " 小时 " + M + " 分 " + S + " 秒 ";

    }

	show_site_runtime();

</script>



</body>



</html>
