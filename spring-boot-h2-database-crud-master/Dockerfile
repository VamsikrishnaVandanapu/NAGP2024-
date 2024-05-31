FROM openjdk:17-jdk-alpine
EXPOSE 8080
ADD target/springboot-crud-h2-k8s.jar springboot-crud-h2-k8s.jar
ENTRYPOINT ["java","-jar","/springboot-crud-h2-k8s.jar"]