MAINTAINER belHak GitHub: https://github.com/belHak
FROM toothpasteeater/default-java-11:latest
ADD target/eureka-application.jar eureka-application.jar
EXPOSE 8761
ENTRYPOINT ["java","-jar","eureka-application.jar"]