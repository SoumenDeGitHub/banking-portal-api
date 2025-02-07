FROM openjdk:17
WORKDIR/app
COPY ./app
RUN mvn clean package
appplication
EXPOSE 8080
CMD ["java", "-jar", "target/bankingportal.jar"]
