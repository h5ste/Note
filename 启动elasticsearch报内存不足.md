# jvm.options

### 修改elasticsearch和logstash安装目录下的config里的jvm.options
### 打开后找到下面内容
-Xms1g
-Xmx1g
  
  
## 解决办法修改：

> -Xms340m
> -Xmx340m

修改为340m  让它们平均分配我虚拟机的1G内存，当然你也可以增大自己的虚拟机内存

2.我自己改成了4G  【解决了问题】

> -Xms4g
> -Xmx4g
