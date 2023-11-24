# Descripcion de este repositorio

Se dara una breve descripcion del uso de docker en jenkins las ventajas y desventajas.Contendra 2 pipeline cada uno con una estructura basica


# Estructura Jenkins con docker

![Diagrama](https://github.com/Andherson333333/CI-CD/blob/main/Jenkins/jenkins-docker/imagenes/docker-jenkins.JPG)

 **como se puede ver en el diagrama se puede hacer mas de 1 estructura :**
   - Jenkins-node
   - Jenkins-docker


# Pipeline 

Si desea saber mas de estas configuraciones puede consultar la pagina oficial https://www.jenkins.io/doc/book/pipeline/docker/

-  `Jenkinsfile-1(Customizing the execution environment)` Permite definir fácilmente imágenes de Docker como el entorno de ejecución para una Etapa o el Pipeline completo.
- Jenkins seleccionará automáticamente el contenedor especificado y ejecutará las etapas definidas en él.

-  `Jenkinsfile-2 (Using multiple containers)`Permite combinar Docker y Pipeline para utilizar múltiples tecnologías en un Jenkinsfile.

# Comparación: Jenkins en Docker vs. Jenkins en el Host

## Ventajas

### Jenkins en Docker
- **Portabilidad:** Facilita la portabilidad de Jenkins y sus configuraciones entre entornos.
- **Escalabilidad:** Permite escalar Jenkins y sus agentes mediante la orquestación de contenedores.
- **Despliegue Rápido:** Facilita el despliegue rápido y la actualización de Jenkins y sus plugins mediante imágenes Docker.
- **Versionado de Configuración:** Permite versionar la configuración de Jenkins a través de versiones de imágenes de contenedor.

### Jenkins en el Host
- **Rendimiento Potencial:** Puede tener un rendimiento ligeramente mejor al ejecutarse directamente en el host.
- **Integración Compleja:** La integración puede ser más directa con los recursos del host.
- **Complejidad de Redirección:** Acceso directo a recursos del host sin redirección de puertos.
- **Control Directo del Host:** Mayor control sobre el entorno del host.

## Desventajas

### Jenkins en Docker

- **Complejidad de Redirección:** Requiere configuraciones de red para redirigir puertos y conectar servicios.
- **Control Directo del Host:** Menos control directo sobre el host, ya que Docker agrega una capa de abstracción.

### Jenkins en el Host
- **Integración Compleja:** La integración puede ser más directa con los recursos del host.
- **Configuración Directa:** Configuración más directa en el entorno del host.

Es importante destacar que la elección entre Jenkins en Docker o en el host depende de los requisitos específicos del proyecto, la preferencia del equipo y las características del entorno. Ambas opciones tienen ventajas y desventajas, y la mejor elección puede variar según el caso de uso.








