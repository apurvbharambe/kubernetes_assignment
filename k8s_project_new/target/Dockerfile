FROM tomcat:9-jre8
# we are using tomcatserver which is used to deploy java applications
# Set the working directory
WORKDIR /usr/local/tomcat

# Copy your WAR file to the Tomcat webapps directory and rename it to ROOT.war
COPY docker-java-sample-webapp-1.0-SNAPSHOT.war webapps/ROOT.war

# Expose the port that Tomcat runs on
EXPOSE 8080

# Start Tomcat
CMD ["catalina.sh", "run"] 