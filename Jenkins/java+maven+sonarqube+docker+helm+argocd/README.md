# Descripcion del repostiorio

En la carpeta spring-boot-app se encuentra la aplicacion y el jenkinfile , habra 2 jenkinfile.

**Jenkinsfile**
   -  Jenkinsfile-1 tendra una instalacion de docker , es decir jenkins es un contenedor.
   -  Jenkinsfile-2 tendra una instalacion en el host jenkins no sera contenedor.


# Estructura del pipeline 
![Diagrama](https://github.com/Andherson333333/CI-CD/blob/main/Jenkins/java%2Bmaven%2Bsonarqube%2Bdocker%2Bhelm%2Bargocd/imagenes/jenkins-maven.JPG)

#  **Instalacion necesario**
   -  Java aplicacion code hosted sobre un repositorio git.
   -  Jenkins server.
   -  Kubernetes cluster.
   -  Helm package manager.
   -  Argo CD

#  **Instalacion en jenkins**
   -  Git plugin
   -  Maven plugin
   -  Pipeline plugin
   
# **Definir etapas del pipeline:**
   - Stage 1: Verifica los repositorios.
   - Stage 2: Construye la aplicación Java.
   - Stage 3: Escanea la aplicación con SonarQube.
   - Stage 4: Verifica el Quality Gate en SonarQube.
   - Stage 5: Construye y etiqueta la imagen Docker.
   - Stage 6: Inicia sesión en Docker Hub y realiza push de la imagen.
   - Stage 7:Actualiza el despliegue en ArgoCD.




