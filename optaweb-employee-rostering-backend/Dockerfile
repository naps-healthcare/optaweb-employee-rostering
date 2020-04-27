FROM adoptopenjdk/openjdk8:ubi-minimal-jre
COPY target/*-exec.jar /opt/app/optaweb-employee-rostering.jar
WORKDIR /opt/app
CMD ["java", "-Xms1024m", "-Xmx2048m", "-Xss256k", "-jar", "optaweb-employee-rostering.jar"]
EXPOSE 8080
