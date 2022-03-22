# CyberChef
Este repositorio contiene todo lo necesario para poder construir una imagen de Docker que despliega [CyberChef](https://github.com/gchq/CyberChef).

## Generar la imagen

```sh
$ docker build -t mycyberchef
```

## Arrancar un contenedor

Si has construido localmente la imagen, el comando que debes utilizar es:
```sh
$ docker run -d -p 8080:8080 --name cyberchef mycyberchef
```
Si no quieres construirte la imagen, puedes utilizar una ya construida que se encuentra publicada en [Docker hub](https://hub.docker.com/r/informaticodelaverno/cyberchef).

# Notas
Si arrancas el contenedor tal y como se indica anteriormente, la ruta con la que se accede a la herramienta es:
- http://localhost:8080/CyberChef_v9.32.3.html