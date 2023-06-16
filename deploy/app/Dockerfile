FROM openjdk:8-jdk-alpine
ARG buildver=0.5.0

#RUN ./gradlew build -x test
COPY  springdemo-0.5.0.jar /app/springdemo.jar
#RUN apt-get update -y 
#RUN  apt-get install libtcnative-1
ENTRYPOINT ["java", "-jar", "/app/springdemo.jar"]
