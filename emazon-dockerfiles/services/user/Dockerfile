MAINTAINER belHak GitHub: https://github.com/belHak
FROM toothpasteeater/default-java-11:latest
ADD target/user-application.jar user-application.jar
EXPOSE 8082
ENTRYPOINT ["java","-jar","user-application.jar"]