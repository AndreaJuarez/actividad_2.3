# INSTRUCCIONES

* Creación de imagen
```bash
docker build -t regresionlineal:v1 .
```

* Creación del contenedor
```bash
docker run -it -p 8080:8080 -v "$PWD"/code/:/home/code/ --name gitpod_rl1 -h rl1 regresionlineal:v1
```