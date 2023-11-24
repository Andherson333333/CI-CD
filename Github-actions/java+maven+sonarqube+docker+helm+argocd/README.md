# Descripcion del repostiorio

En la carpeta workflows se encuentra la configuracion de github-actions

# Estructura workflows
![Diagrama](https://github.com/Andherson333333/CI-CD/blob/main/Github-actions/java%2Bmaven%2Bsonarqube%2Bdocker%2Bhelm%2Bargocd/Imagenes/github-maven.JPG)

#  **Instalacion necesario**
   -  Kubernetes cluster.
   -  Helm package manager.
   -  Argo CD
  
# **Definir etapas del workflows:**
   - Stage 1: Verifica los repositorios.
   - Stage 2: Construye la aplicación Java y hacer test unitarios Junit.
   - Stage 3: Escanea la aplicación con SonarCloud.
   - Stage 4: Verifica el Quality Gate en SonarCloud.
   - Stage 5: Construye y etiqueta la imagen Docker.
   - Stage 6: Inicia sesión en Docker Hub y realiza push de la imagen.
   - Stage 7: Actualiza el despliegue en ArgoCD.
