## Jemter

> 学好Jmeter，做好测试

&nbsp;&nbsp;**使用说明：**

```
大致是去官网下载好解压包，然后配置到环境变量去，控制台输入jmeter。后面的话是先创建一个线程组，然后在线程组里可以放网络请求和数据库请求啥的，为了经可能模拟的到位，还可以再其上一层放if选择器，再添加一个结果查看器就好了。
```

&nbsp;&nbsp;**环境变量配置：**
```
变量名：JMETER_HOME  
变量值：Jmeter安装目录  
变量名：CLASSPATH  
变量值：%JMETER_HOME%\lib\ext\ApacheJMeter_core.jar;%JMETER_HOME%\lib\jorphan.jar;  %JMETER_HOME%\lib/logkit-2.0.jar;
```