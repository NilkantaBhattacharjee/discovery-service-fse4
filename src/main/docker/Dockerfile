FROM openjdk:8
VOLUME /tmp
ARG JAR_FILE=build/libs/discovery-service.jar
EXPOSE 8761
COPY ${JAR_FILE} discovery-service.jar
ENTRYPOINT ["java","-jar","/discovery-service.jar"]