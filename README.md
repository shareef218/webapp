# Tomcat Java Web App with Jenkins CI/CD

A template Java Servlet project configured to automatically build with Maven and deploy to Apache Tomcat via a Jenkins pipeline.

## Jenkins Setup Requirements
1. **Tools Configured:** Maven 3 and JDK 17 mapped in Jenkins Global Tool Configuration.
2. **Credentials Added:** Username/Password credentials stored with ID `tomcat-credentials` matching a Tomcat user with the `manager-script` role.
3. **Tomcat Manager:** Remote script execution allowed in Tomcat's `tomcat-users.xml`.
