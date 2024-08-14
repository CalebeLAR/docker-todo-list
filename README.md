# Docker Todo List
Neste projeto, eu conteinerizei aplicações, criei conexões entre elas e orquestrei seu funcionamento.  

Trabalhei com uma aplicação full-stack que é um aplicativo de tarefas! Que está no repositório `todo-app`  

Minha tarefa foi conteinerizar essa aplicação para que ela funcionasse corretamente. Desenvolvi os arquivos de configuração para cada parte específica: Front-end, Back-end e também para um aplicativo de teste que valida se as aplicações estão se comunicando.  

Eu criei as imagens para as aplicações e configurei essas imagens utilizando o Docker Compose. Para isso, utilizei uma série de comandos do Docker, que variaram em diferentes níveis de complexidade.  

Cada comando foi escrito em seu próprio arquivo.

Segui os seguintes passos:

Li o requisito e criei um arquivo chamado commandN.dc no diretório docker-commands, onde N é o número do requisito. Por exemplo:

    Requisito 1: ./docker/docker-commands/command01.dc  
    Requisito 2: ./docker/docker-commands/command02.dc  
    Requisito 3: ./docker/docker-commands/command03.dc  

No arquivo, escrevi o comando da CLI (Interface de Linha de Comando) do Docker que resolve o requisito. Um exemplo de como ficou meu arquivo:

```bash
docker network inspect bridge
```
## sobre o desenvolvimento
_Primeiro projeto desenvolvido no módulo de Back-End durante minha formação na escola de tecnologia da Trybe, que elaborou os requisitos para o projeto e forneceu a aplicação que foi conteinerizada._