# 修改zkHost的值
spring-context-thrift-client.xml
spring-context-thrift-server.xml
修改配置文件中的zkHost的值
# 修改log4j.properties格式
%c{1}删掉{1}，日志中看类的全限定名
# 修改Client.java
* 使用TThread看client线程持续调用
* 使用simple()看简单的thrift client-server调用