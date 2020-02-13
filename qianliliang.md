本地Idea编译说明：
1、使用自带的gradlew脚本

2、注意将`spring-core` and `spring-oxm` Task的other里的RepackJar设置在Before等前；

3、如果Rebuild Project，可以使用`./gradlew :spring-oxm:compileTestJava`再次进行操作

