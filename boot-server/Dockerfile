FROM java:8-jre
MAINTAINER NIJO GEORGE P <nijomon@gmail.com>

ADD ./target/angular-boot-app.jar /app/
CMD ["java", "-Xmx200m", "-jar", "/app/angular-boot-app.jar"]

EXPOSE 6000