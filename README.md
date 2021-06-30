# docker-nodejs
Aprendiendo conceptos de Docker usando una app de Nodejs

Mi imagen : https://hub.docker.com/repository/docker/ricardotovar/node-restapi

Comandos:

docker pull ricardotovar/node-restapi:v1

docker run -p 4000:3000 node-restapi

Uso 4000:3000, por que la aplicacion internamente escucha en el puerto 3000 y con 4000 yo puedo usarlo en un navegador.
