MAINTAINER belHak GitHub: https://github.com/belHak
FROM toothpasteeater/default-java-11:latest
ADD target/gateway-application.jar gateway-application.jar
EXPOSE 8888
ENTRYPOINT ["java","-jar","gateway-application.jar"]