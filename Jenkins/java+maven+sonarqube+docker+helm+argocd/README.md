# Estructura del pipeline 
![Diagrama](https://github.com/Andherson333333/CI-CD/blob/main/Jenkins/java%2Bmaven%2Bsonarqube%2Bdocker%2Bhelm%2Bargocd/imagenes/jenkins-maven.JPG)

# Instalaciones necesarias

Java aplicacion código alojado en un repositorio Git

Jenkins server

Kubernetes cluster

Helm package manager

Argo CD


# **Definir etapas del pipeline:**
   - Stage 1: consulte el código fuente de Git..
   - Stage 2: ree la aplicación Java con Maven.
   - Stage 3: ejecutar pruebas unitarias usando JUnit y Mockito.
   - Stage 4: ejecute el análisis de SonarQube para verificar la calidad del código..
   - Stage 5: empaquete la aplicación en un archivo JAR..
   - Stage 6: implementar la aplicación en un entorno de prueba utilizando Helm.
   - Stage 7: ejecutar pruebas de aceptación del usuario en la aplicación implementada..
   - Stage 8: ejecutar pruebas de aceptación del usuario en la aplicación implementada..




