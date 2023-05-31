# CICD_Pipeline

Languages and FrameWorks: Java, Spring Boot, Maven, AWS EC2, Docker, Kubernetes, Jenkins, SonarQube, Argo CD. 

1. This comprehensive Jenkins pipeline offers complete automation for the CI/CD workflow of a Java application. 
2. It seamlessly handles every step, starting from checking out the source code all the way to deploying the application in production. 
3. The pipeline leverages well-known and widely-used tools such as SonarQube, Argo CD, Docker, and Kubernetes, ensuring a streamlined and efficient development and deployment process for your Java application.

Steps Implemented:

1. Installed the necessary Jenkins plugins: Git, Maven Integration, Pipeline, and Kubernetes Continuous Deploy plugin
2. Created a new Jenkins pipeline and configured it with the Git repository URL for the Java application. Also, added a Jenkinsfile to the Git repository to define the pipeline stages.
3. Jenkins Pipeline stages:
        Stage 1: Checkout the source code from Git.
        Stage 2: Build the Java application using Maven.
        Stage 3: Run unit tests using JUnit and Mockito.
        Stage 4: Run SonarQube analysis to check the code quality.
        Stage 5: Package the application into a JAR file.
        Stage 6: Promote the application to a production environment using Argo CD.
4. Installed Argo CD on the Kubernetes cluster. Set up a Git repository for Argo CD to track the changes and Kubernetes manifests.
5. Configured Jenkins pipeline to integrate with Argo CD, added the Argo CD API token to Jenkins credentials.
6. Triggered the Jenkins pipeline to start the CI/CD process for the Java application. Monitored the pipeline stages and fixed any issues that arised.



