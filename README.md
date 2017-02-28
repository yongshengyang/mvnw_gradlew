Maven Wrapper:
Maven Wrapper: mvnw,它的原理是在maven-wrapper.properties文件中记录你要使用的maven版本，当用户执行mvnw clean 命令时，发现当前用户的maven版本和期望的版本不一致，那么就下载期望的版本;
生成命令：mvn -N io.takari:maven:wrapper -Dmaven=3.3.3 表示我们期望使用的maven的版本为3.3.3
参考： http://www.javacoder.cn/?p=759

Gradle Wrapper
Gradle Wrapper允许你在任何没有安装Gradle的系统中执行Gradle的构建脚本。这个对于持续集成服务器是非常方便的。Gradle也适用于开源项目，以降低其构建的门槛。Wrapper同时也适用于企业项目。Gradle构建的客户机不需要任何配置，同时也可以强制限制构建使用指定的Gradle版本，从而最小化由于构建环境差异可能带来的问题。
生成命令： gradle wrapper
参考： http://jingyan.baidu.com/article/d5c4b52beba364da560dc5a9.html