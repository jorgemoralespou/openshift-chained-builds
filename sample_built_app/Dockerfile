FROM corporatebuilder:latest

COPY files/app.jar /opt/openshift/app.jar
CMD ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "/opt/openshift/app.jar"]
