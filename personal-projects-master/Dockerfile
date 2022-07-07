FROM openjdk:8-jdk-slim
RUN echo "Test"
RUN  mkdir /opt/app
RUN echo "RUN One"
RUN echo "RUN Two"
WORKDIR /opt/user
COPY target/*.jar /opt/personal-projects.jar
CMD ["java", ".jar", "personal-projects.jar"]
EXPOSE 8080
