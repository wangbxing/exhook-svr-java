# exhook-svr-java
exhook的java钩子例子

## 环境
- emqx 5.0.11版本，更高级版本可能不一致（例如钩子方法等）
- JDK version 8 or higher
- Maven

## 运行
```
mvn package
java -jar target/exhook-svr-java-1.0-jar-with-dependencies.jar
```
## 使用
a、启动服务后，在Dashboard的ExHook列表页新建钩子，配置url，本项目默认端口是9000，例如：http://192.168.0.121:9000
b、在配置文件中配置，目前没有实现