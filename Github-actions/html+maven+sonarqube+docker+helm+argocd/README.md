# Descripcion del repostiorio

En el archivo CI-CD.yml se encuentra la configuracion de github-actions

# Estructura workflows
![Diagrama]()

#  **Instalacion necesario**
   -  Kubernetes cluster.
   -  Helm package manager.
   -  Argo CD
  
# **Definir etapas del workflows:**
   - Stage 1: Verifica los repositorios.
   - Stage 2: Escanea la aplicación con SonarCloud.
   - Stage 3: Verifica el Quality Gate con SonarCloud.
   - Stage 4: Construye y etiqueta la imagen Docker.
   - Stage 5: Inicia sesión en Docker Hub y realiza push de la imagen.
   - Stage 6: Actualiza el despliegue en ArgoCD.
