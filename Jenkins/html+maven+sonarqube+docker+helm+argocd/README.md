# Uso de este repositorio

Dentro de la carpeta app , se encuntra el jenkinsfile y la aplicacion 


# Estructura del pipeline 
![Diagrama](https://github.com/Andherson333333/CI-CD/blob/main/Jenkins/html%2Bmaven%2Bsonarqube%2Bdocker%2Bhelm%2Bargocd/imagenes/html.JPG)

#  **Instalacion necesario**
   -  html codigo en los repositorios git.
   -  Jenkins server.
   -  Kubernetes cluster.
   -  Helm package manager.
   -  Argo CD

#  **Instalacion en jenkins**
   -  Git plugin
   -  Pipeline plugin
   
# **Definir etapas del pipeline:**
   - Stage 1: Verifica los repositorios.
   - Stage 2: Escanea la aplicación con SonarQube.
   - Stage 3: Verifica el Quality Gate en SonarQube.
   - Stage 4: Construye y etiqueta la imagen Docker.
   - Stage 5: Inicia sesión en Docker Hub y realiza push de la imagen.
   - Stage 6:Actualiza el despliegue en ArgoCD.
