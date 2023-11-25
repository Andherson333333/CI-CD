# Uso de este repositorio

En la carpeta workflows se encuntra la configuracion github-actions

# Que es Github actions

GitHub Actions es un servicio de integración continua y despliegue continuo (CI/CD) ofrecido por GitHub. Permite la automatización de flujos de trabajo para el desarrollo de software directamente en el entorno de GitHub. Con GitHub Actions, puedes definir flujos de trabajo que se activan por eventos específicos, como confirmaciones de código, solicitudes de extracción (pull requests), creación de etiquetas, entre otros.

# Como usar github actions

Para utilizar GitHub Actions y automatizar flujos de trabajo, sigue estos pasos:

## Configuración de GitHub Actions

### 1. Crear una Carpeta y Archivo de Configuración YAML
   - Crea una carpeta llamada `.github/workflows` en la raíz de tu repositorio.
   - Dentro de esta carpeta, crea un archivo YAML para la configuración de la acción, por ejemplo, `mi_flujo.yaml`.

   **Configuración Manual o Predeterminada:**
   - Puedes crear manualmente la carpeta y el archivo YAML o simplemente dirigirte a la sección "Actions" en tu repositorio en GitHub. GitHub detectará automáticamente la falta de un flujo de trabajo y te sugerirá crear uno predeterminado.

### 2. Definir Eventos para Activar la Acción
   - En el archivo YAML, define los eventos que activarán tu acción. Por ejemplo, puedes configurar la acción para ejecutarse en cada push o en eventos específicos.

### 3. Configurar los Trabajos y Pasos
   - Dentro del archivo YAML, define los trabajos (jobs) y pasos (steps) necesarios para tu acción.

### 4. Commit y Observar la Acción en GitHub
   - Realiza un commit con tus cambios en el archivo YAML.
   - Dirígete a la sección "Actions" en tu repositorio de GitHub para observar la ejecución de tu flujo de trabajo.









