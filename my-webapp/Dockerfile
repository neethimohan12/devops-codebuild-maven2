FROM openjdk:8
ADD target/my-webapp.war /my-webapp.war
RUN echo "This is a Docker Build Jenkins Step" > out.txt
ENTRYPOINT ["java", "-jar","my-webapp.war"]
EXPOSE 8080