![GitHub repo size](https://img.shields.io/github/repo-size/JaimeDevS/api-crud-springboot?style=plastic)

# Comandos GIT

Exemplo de alguns comandos do GIT.

![Java](https://github.com/JaimeMS/JaimeMS/blob/main/img/git2.png) 

## Pré-requisitos

* [Git](https://git-scm.com/downloads) - Download do git
* [Github](https://github.com/) - Criar conta no github

## Começando

#### INICIALIZAR O REPOSITÓRIO
- git init 

#### CONFIGURANDO O REPOSITÓRIO
- git config --global user.email 
- git config --global user.name

#### ADICIONAR O ARQUIVO NO CONTROLE DE VERSÃO
- git add "nome do arquivo"
- git add .

#### CRIANDO VERSÃO DO CÓDIGO COM COMMIT
- git commit -m "descrição"
 
#### ENVIAR ALTERAÇÕES USANDO O GIT PUSH
- git push
- git remote add origin https://github.com/JaimeMS/projeto1
- git push --set-upstream origin master
- git push -u origin master

git remote add origin https://github.com/JaimeMS/LayoutAdmin.git

#### CICLO DE ATUALIZAÇÃO DE CÓDIGO 
- git add .
- git commit -m ""
- git push

#### VERIFICAR HISTÓRICO DE ATUALIZAÇÕES
- git log
- git log --oneline
- git reflog

#### COMO NAVEGAR ENTRE AS VERSÕES DO CÓDIGO
- git reset --hard 2a31c00

#### COMO CRIAR BRANCHES
- git branch
- git branch stagin
- git checkout 'stagin'
- git push --set-upstream origin staging

#### GIT MERGE COMO UNIR O CÓDIGO 
- entrar na branch que vai receber a atualização
- quando entrar na branch principal puxar as atualizações da nuvem
- git pull
- git merge nomeDaBrach

#### CRIA UMA NOVA BRANCH COPIANDO A ATUAL
- git checkout -b NomeDaBranch master

#### OUTROS
- git remote -v //mostra os repositórios remotos

# Resumo
1. git pull da branch principal
2. gerar uma nova branch a partir da branch principal
3. trabalhar e adicionar novas funcionalidades na nova branch
4. finalizar o trabalho na branch temporária
5. git checkout na branch principal
6. git pull
7. mergiar o código da branch temporária com a branch principal
8. git push da branch principal

