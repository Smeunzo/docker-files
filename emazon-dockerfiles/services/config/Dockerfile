MAINTAINER belHak GitHub: https://github.com/belHak
FROM toothpasteeater/default-java-11:latest
ADD target/config-application.jar config-application.jar
EXPOSE 8889
ENTRYPOINT ["java","-jar","config-application.jar"]