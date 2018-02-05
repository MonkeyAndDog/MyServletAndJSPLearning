# Servlet和JSP学习
---
## 编写Servlet和配置Servlet
1. Servlet要继承自HttpServlet，同时要重写其中的一些个方法如：doGet，doPost，默认情况下直接在浏览器地址栏中访问使用的是get方法
2. 配置servlet
   ├── 使用注解<br>
   ├── 使用web.xml<br>
3. 部署配置<br>
   ├── 目录<br>
   │    ├── WEB-INF目录下的是对外界不可直接访问的目录<br>
   │    ├── classes 编译好的类文件<br>
   │    └── lib 库文件，目录名称不可变<br>
   ├── 导出为 war 文件，然后放到Tomcat的webapp目录下，重启Tomcat后自解压<br>
   ├── 未完待续<br>
   

	