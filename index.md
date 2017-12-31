<html !doctype html>
	<head>
		<meta getchar="utf-8">
		<style type="text/css">
		#qwe
		{MARGIN-RIGHT: auto;
		MARGIN-LEFT: auto;
		height:200px;
		width:550px;
			}
		</style>
		
	</head>
	<title>project 4 CS1707谢文彬_网页制作与托管
	</title>
	<body>
	<div id="qwe">
		<div>
			<span style= font-size:30>我的专业志趣</span><hr/>
			<pre style=font-size:20 style=width:550px >
	   	    第一次课后作业
尊敬的老师：
    您好。
    当初选择计算机专业主要是因为自己对计算机方面的知识
比较感兴趣，然后听说计算机的工作前景也比较好，所以才选
择计科。计算机当然用过，以前的话主要用来打游戏、看视频
、聊天吧。网站就百度比较常用，用来查资料。Office的软件、
QQ、微信、等等都用过。游戏的话比较喜欢沙盒、RPG、MOBA、
RTS类的游戏。大学之前都没有学习过编程，也不会网页技术。
希望计导能帮我了解到计算机的知识，也希望自己能在计科学
习到很多专业知识，成为大佬。
此致
敬礼	
						谢文彬
						17计科
					 2017年9月22日
			</pre>
		<hr/>
		</div>
		<div>
		<span style= font-size:30 height="35">project 1 专业排版项目</span><a href="https://pan.baidu.com/s/1jInaKsA">→下载链接←</a></br>
		<span style= font-size:30 height="35">project 2 数据处理项目</span><a href="https://pan.baidu.com/s/1c1ZFO6O">→下载链接←</a></br>
		<span style= font-size:30 height="35">project 3 我的家乡项目</span><a href="https://pan.baidu.com/s/1c1OQ27e">→下载链接←</a></br>
		</div>
		<hr/>
		<div><span style= font-size:30 height="35">ppt展示</span></br>
		<a href="">
		<!--<embed width="550" height="600" src="计科 谢文彬 Labprojecttwo.pdf"> </embed>-->
		</div></br><hr/>
		<div>
			<span style= font-size:30 height="35">C程序设计作业</span>
			<hr/>
			</br>
			<span style= font-size:25 height="35">Problem Description</span>
			<p>事情是这样的——HDU有个网名叫做8006的男性同学，结交网友无数，最近该同学玩起了浪漫，同时给n个网友每人写了一封信，这都没什么，要命的是，他竟然把所有的信都装错了信封！注意了，是全部装错哟！

现在的问题是：请大家帮可怜的8006同学计算一下，一共有多少种可能的错误方式呢？
</p>
			<span style= font-size:25 height="35">Input</span>
			<p>输入数据包含多个多个测试实例，每个测试实例占用一行，每行包含一个正整数n（n大于1且小于等于20），n表示8006的网友的人数。</p>
			</br>
			<span style= font-size:25 height="35">Output</span>
			<p>对于每行输入请输出可能的错误方式的数量，每个实例的输出占用一行。</p>
			</br>
			<span style= font-size:25 height="35">Code</span>
			<pre style= font-size:20 height="20">>
#include<stdio.h>
int main()
{
    long long a[21]={0,0,1},n=3;
    for(;n<=20;n++)
        a[n]=a[n-1]*(n-1)+(n-1)*a[n-2];
    while(scanf("%d",&n)!=EOF)
        printf("%lld\n",a[n]);
    return 0;
}
			</pre>
		</div>
		<hr/>
	</div>
	</body>
</html>
