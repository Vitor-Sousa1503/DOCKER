# DOCKER
**10 comandos docker linux**

## 1° docker imagem prune
**Remove imagens penduradas ou sem tag**

## 2° docker image prune -a
**Remove todas as imagens que não estãpo sendo usadas por nenhum container**

## 3° docker system prune
**Remove todas os containers parados, redes não usadas por containers, imagens dangling e o cache dw build**

## 4° docker image rm nome-da-imagem
**Remove uma imagem específica pelo nome**

## 5° docker rm container
**Copia Remove um container em execução**

## 6° docker swarm leave
**Sai de um swarm**

## 7° docker stack rm nome-do-stack
**Remove um stack do Swarm**

## 8° docker volume rm $ (docker volume la -f dangling=true -q)
**Remove todos os volumes dangling**

## 9° docker rm $ (docker ps -a -q)
**Remove todos os containers parados**

## 10° docker kill $ (docker ps -q)
**Interrompe todos os containers em execução**
