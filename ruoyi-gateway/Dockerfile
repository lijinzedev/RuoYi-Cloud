FROM openjdk:1.8
MAINTAINER Curiosity
ADD ./target/ruoyi-gateway-2.4.0.jar gateway.jar
EXPOSE 8080
ENTRYPOINT ["java","-jar","-Xmx512m -Xms128m -Xmn64m -Xss64m -Dfile.encoding=UTF-8","gateway.jar"]