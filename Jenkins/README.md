# Que es jenkins 

Jenkins es una herramienta de automatización de código abierto ampliamente utilizada para facilitar el proceso de integración continua (CI) y despliegue continuo (CD) en el desarrollo de software. Es un servidor de automatización que ayuda a construir, probar y desplegar proyectos de software de manera automatizada.

# Instalacion de Jenkins

Se puede realizar de 2 formas 

## 1 Nativa en el sistema operativo

Si desea Instalar jenkins verificar primero la documentacion oficial https://www.jenkins.io/doc/book/installing/, igual puede copiar los siguiente comando y se instalara 

```
sudo wget -O /usr/share/keyrings/jenkins-keyring.asc \
https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key
```

```
echo deb [signed-by=/usr/share/keyrings/jenkins-keyring.asc] \
https://pkg.jenkins.io/debian-stable binary/ | sudo tee \
/etc/apt/sources.list.d/jenkins.list > /dev/null
```

```
sudo apt-get update
sudo apt-get install jenkins
```

## 2 Usando docker para desplegar jenkins

Verificar primero la imagen oficial en https://hub.docker.com/search?q=jenkins , una ves verificada se procede a descargar
```
docker pull jenkins/jenkins 
```
siempre es recomendable descargar las imagenes con un tag para tener mejor control sobre las versiones 

`docker pull jenkins/jenkins:<version>-<jdk>`

# Uso de este repositorio

Cada carpeta es un pipeline distinto , dentro encontrara una explicacion del pipeline 
