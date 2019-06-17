### Eureka Server 源码分析

代码入口在org.springframework.cloud:spring-cloud-netflix-eureka-server:{版本}.jar下<br>
META-INF目录下的spring.factories文件内；<br>
配置为org.springframework.boot.autoconfigure.EnableAutoConfiguration=\
  org.springframework.cloud.netflix.eureka.server.EurekaServerAutoConfiguration
<br>
<br>
![avatar](https://github.com/chenluxing/sourceCode/images/eurekaServer.jpg)