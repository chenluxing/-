### Feign 源码分析

代码入口在org.springframework.cloud:spring-cloud-netflix-core:{版本}.jar下<br>
META-INF目录下的spring.factories文件内；<br>
配置为org.springframework.boot.autoconfigure.EnableAutoConfiguration=\<br>
   org.springframework.cloud.netflix.archaius.ArchaiusAutoConfiguration,\<br>
   org.springframework.cloud.netflix.feign.ribbon.FeignRibbonClientAutoConfiguration,\<br>
   org.springframework.cloud.netflix.feign.FeignAutoConfiguration,\<br>
   org.springframework.cloud.netflix.feign.encoding.FeignAcceptGzipEncodingAutoConfiguration,\<br>
   org.springframework.cloud.netflix.feign.encoding.FeignContentGzipEncodingAutoConfiguration,\<br>
   org.springframework.cloud.netflix.hystrix.HystrixAutoConfiguration,\<br>
   org.springframework.cloud.netflix.ribbon.RibbonAutoConfiguration,\<br>
   org.springframework.cloud.netflix.rx.RxJavaAutoConfiguration,\<br>
   org.springframework.cloud.netflix.metrics.servo.ServoMetricsAutoConfiguration
<br>
<br>
![avatar](https://github.com/chenluxing/sourceCode/blob/master/images/feign_1.png?raw=true)
<br>
![avatar](https://github.com/chenluxing/sourceCode/blob/master/images/feign_2.png?raw=true)
<br>
![avatar](https://github.com/chenluxing/sourceCode/blob/master/images/feign_3.png?raw=true)

