# MyWebApp

利用Eclipse 新建可视化Web应用
1.打开Eclipse，点击“File”菜单，或者通过工具栏的“New”创建Dynamic Web Project，弹出向导对话框
填入Project name后，并点击”New Runtime”,如下图所示：

2.出现New Server Runtime Environment向导对话框,选择“Apache Tomcat v8.0”,点击next按钮,如下图：

3.选择Tomcat安装文件夹

4.返回New Server Runtime Environment向导对话框，点击finish即可

5.返回Dynamic Web Project向导对话框，点击finish即可

6.这样新建一个Dynamic Web Project就完成了

src文件夹用来存放Java服务端的代码，例如:读取数据库MySQL中的数据
WebContent文件夹则用来存放前端页面文件，例如：前端页面资源css、img、js，前端JSP页面
7.下载mysql-connector-java-5.1.40.zip
解压后cp mysql-connector-java-5.1.40-bin.jar 到MyWebApp/WebContent/WEB-INF/lib/下

上述操作完成后，即可开发可视化应用了。
