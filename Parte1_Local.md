# Tutorial Git - Desenvolvimento Colaborativo

## Sumário

1. [Configuração Inicial](#1-configuração-inicial)
2. [Inicialização de um Repositório](#2-inicialização-de-um-repositório)
3. [Adição de Arquivos ao Repositório](#3-adição-de-arquivos-ao-repositório)
4. [Realização de Commits](#4-realização-de-commits)
5. [Verificação do Status](#5-verificação-do-status)
6. [Histórico de Commits](#6-histórico-de-commits)
7. [Criação de Branches](#7-criação-de-branches)
8. [Merge de Branches](#8-merge-de-branches)
9. [Remoção de Arquivos](#9-remoção-de-arquivos)


## Configuração Inicial

Antes de começar a usar o Git, é necessário configurar suas informações pessoais. Execute os seguintes comandos no terminal:

```bash
git config --global user.name "Seu Nome"
git config --global user.email "seu@email.com"
bash
## Inicialização de um Repositório
Para iniciar um repositório Git em um diretório existente, utilize o seguinte comando:



git init
Este comando cria um repositório Git local no diretório atual.

##Adição de Arquivos ao Repositório
Para adicionar arquivos ao controle de versão, utilize o comando:

bash

git add nome-do-arquivo
Se você quiser adicionar todos os arquivos no diretório, use:

bash

git add .
##Realização de Commits
Após adicionar os arquivos, é necessário realizar um commit para salvar as alterações. Execute o seguinte comando:

bash

git commit -m "Mensagem do Commit"
Certifique-se de fornecer uma mensagem clara e concisa que descreva as alterações realizadas.

##Verificação do Status
Para verificar o status do seu repositório e visualizar as alterações não commitadas, utilize:

bash

git status
##Histórico de Commits
Para visualizar o histórico de commits, use o comando:

bash

git log
Este comando exibe informações detalhadas sobre todos os commits no repositório.

##Criação de Branches
Branches são úteis para desenvolver novas funcionalidades sem afetar a branch principal. Crie uma nova branch com:

bash

git branch nome-da-branch
Em seguida, mude para a nova branch:

bash

git checkout nome-da-branch
Ou combine os dois passos usando:

bash

git checkout -b nome-da-branch
##Merge de Branches
Para mesclar uma branch de volta à branch principal, utilize:

bash

git checkout main
git merge nome-da-branch
Certifique-se de resolver quaisquer conflitos que possam surgir durante o processo de merge.

##Remoção de Arquivos
Se você precisar remover um arquivo do controle de versão, use:

bash

git rm nome-do-arquivo
git commit -m "Remover arquivo"
Este processo também funciona para a remoção de diretórios.
