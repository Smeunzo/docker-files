MAINTAINER belHak GitHub: https://github.com/belHak
FROM toothpasteeater/default-java-11:latest
ADD target/inventory-application.jar inventory-application.jar
EXPOSE 8082
ENTRYPOINT ["java","-jar","inventory-application.jar"]