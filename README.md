【工具介绍】

fastjson版本信息探测是一款简单易用的工具。

该工具可用于探测目标系统fastjson版本信息，内置 dnslog API ，可以顺手探测服务端使用的部分组件依赖

fvc.zip是源码

bin.zip是编译好的jar文件



【工具原理】

利用constant.poc中的poc进行扫描，在通过API对Records进行提取分析判断是否存在漏洞


【使用方法】

注：运行需要Java环境且需要联网，可按需下载jar文件使用，或可下载源码src按需修改后使用，打包方式在源码中打包.txt中，未使用maven，部分依赖需要手动导入。


直接执行命令 java -jar fvc 查看参数

利用poc探测目标系统的fastjson版本信息，还能顺手检测常见依赖，例如：SpringBoot、Tomcat、Groovy、C3P0、mysql-jdbc-5、mysql、mysql-connect-8、Mybatis、tomcat-dbcp、commons-io、aspectjtools等。

<img width="2405" height="1365" alt="image" src="https://github.com/user-attachments/assets/dee2ae47-d288-4421-a418-91d5207783a6" />
<img width="1404" height="870" alt="image" src="https://github.com/user-attachments/assets/75f39045-a396-45f0-af54-0fe8d4946a29" />
