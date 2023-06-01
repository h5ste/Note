
# 免杀exe文件




[https://www.t00ls.com/thread-69464-1-1.html](https://)

>更改文件资源信息免杀时如何快速添加静态资源至我们的木马文件，进一步降低杀软查杀概率，这里分享两个平时用的最多的工具一把梭。


## 静态资源

使用Resource_Hacker工具打开一个正常exe文件，将所有资源保存为RES文件
![](https://hackmd.io/_uploads/rkUSx6HI3.png)






然后打开我们的木马文件导入刚刚的res静态资源
![](https://hackmd.io/_uploads/HyDUl6BUh.png)




还可以更改资源语言修改完成


![](https://hackmd.io/_uploads/r1zPgarL2.png)
数字签名

使用sigthief工具自动复制签名至我们的木马文件，这里复制的qq音乐的签名，当然这里的签名是伪签名。
![](https://hackmd.io/_uploads/S1ideTSUn.png)
