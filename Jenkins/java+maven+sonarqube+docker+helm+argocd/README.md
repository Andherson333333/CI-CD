# Estructura del pipeline 
![Diagrama]()

# Instalaciones necesarias

Java aplicacion código alojado en un repositorio Git
Jenkins server
Kubernetes cluster
Helm package manager
Argo CD


**Definir etapas del pipeline:**
   - Stage 1: Checkout the source code from Git.
   - Stage 2: Build the Java application using Maven.
   - Stage 3: Run unit tests using JUnit and Mockito.
   - Stage 4: Run SonarQube analysis to check the code quality.
   - Stage 5: Package the application into a JAR file.
   - Stage 6: Deploy the application to a test environment using Helm.
   - Stage 7: Run user acceptance tests on the deployed application.
   - Stage 8: Promote the application to a production environment using Argo CD.

1. **Install the necessary Jenkins plugins:**
   1.1 Git plugin
   1.2 Maven Integration plugin
   1.3 Pipeline plugin
   1.4 Kubernetes Continuous Deploy plugin


