# Descripcion del repostiorio

En la carpeta workflows se encuentra la configuracion de github-actions

# Estructura workflows
![Diagrama]()

#  **Instalacion necesario**
   -  Kubernetes cluster.
   -  Helm package manager.
   -  Argo CD
  
# **Definir etapas del pipeline:**
   - Stage 1: Verifica los repositorios.
   - Stage 2: Construye la aplicación Java.
   - Stage 3: Escanea la aplicación con SonarQube.
   - Stage 4: Verifica el Quality Gate en SonarQube.
   - Stage 5: Construye y etiqueta la imagen Docker.
   - Stage 6: Inicia sesión en Docker Hub y realiza push de la imagen.
   - Stage 7:Actualiza el despliegue en ArgoCD.
