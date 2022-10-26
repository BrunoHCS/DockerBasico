# Docker Básico
_O objetivo desse repo é compartilhar alguns comandos básicos de Docker._

* [Site oficial](https://www.docker.com/)
* [Documentação](https://docs.docker.com/)

## Baixa uma imagam
* ```docker pull docker pull ubuntu```
* ```docker pull docker pull nginx```
* ```docker pull docker pull mongodb```

## Baixa e executa uma imagem
* ```docker run -i -t node```
* ```docker run -i -t ubuntu```
* ```docker run -d nginx``` **(baixa a imagem e deixa em background)**

## Lista os containers que estão sendo executados
* ```docker container ls```

## Lista as imagem baixadas
* ```docker images```

## Parar um container que está em background
* ```docker container stop 'hash_do_container'```

## Inicializar um container
* ```docker container start 'hash_do_container'```

## Expor uma porta para um container 
* ```docker run -p 80:80 nginx```
* ```docker run -p 80:80 --name coloque_um_nome_no_container nginx```

## Log
* ```docker logs nome_do_container```

## Remover uma imagem
* ```docker rmi nome_da_imagem ou hash -f```
* ```docker image rm nome_da_imagem ou hash```

## Remover um container
* ```docker container rm 'hash_do_container'```
