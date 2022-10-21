# Docker Básico
_O objetivo desse repo é compartilhar alguns comandos básicos de Docker._

* [Site oficial](https://www.docker.com/)
* [Documentação](https://docs.docker.com/)

## Baixar uma imagem
* ```docker run -it node```
* ```docker run -it ubuntu```
* ```docker run -d nginx``` **(baixa a imagem e deixa em background)**

## Lista os containers ativos
* ```docker ps```

## Lista as imagem baixadas
* ```docker images```

## Parar um container que está em background
* ```docker stop 'hash_do_container'```

## Expor uma porta de um container 
* ```docker run -p 80:80 nginx```
* ```docker run -p 80:80 --name coloque_um_nome_no_container nginx```

## Log
* ```docker logs nome_do_container```

## Remove imagens baixadas
* ```docker rmi nome_da_imagem ou hash -f```
