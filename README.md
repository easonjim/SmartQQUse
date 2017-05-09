# SmartQQUse
使用SmartQQ实现的智能回复  
采用SmartQQ SDK进行开发，官网：[https://github.com/ScienJus/smartqq](https://github.com/ScienJus/smartqq)  
此项目只是集成使用的方法，在com.jsoft.robot.SmartQQUse.Receiver下，依然是官方的例子修改而来。  
要运行此项目，命令如下：  
1、先clone项目到本地  
2、编译项目：mvn compile  
3、运行项目：mvn exec:java -Dexec.mainClass="com.jsoft.robot.SmartQQUse.Receiver"  
4、部署Linux时出现No X11 DISPLAY variable was set, but this program performed an operation which requires it.的问题，解决办法：[http://www.cnblogs.com/EasonJim/p/6832657.html](http://www.cnblogs.com/EasonJim/p/6832657.html)
