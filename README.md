# curso-git-rapido
Repositório para aprender GIT e GITHUB

INSTALAÇÃO
https://git-scm.com/downloads

CRIAR CONTA NO GITHUB
https://github.com/

INICIALIZAR O REPOSITÓRIO
- git init 

ADICIONAR O ARQUIVO NO CONTROLE DE VERSÃO
- git add "nome do arquivo"

CRIANDO VERSÃO DO CÓDIGO COM COMMIT
- git commit -m "descrição"
- git config --global user.email 
- git config --global user.name
 
ENVIAR ALTERAÇÕES USANDO O GIT PUSH
- git push
- git remote add origin https://github.com/JaimeMS/projeto1
- git push --set-upstream origin master

git remote add origin https://github.com/JaimeMS/LayoutAdmin.git

CLICLO DE ATUALIZAÇÃO DE CÓDIGO - 22min
- git add .
- git commit -m ""
- git push

VERIFICAR HISTÓRICO DE ATUALIZAÇÕES
- git reflog

COMO NAVEGAR ENTRE AS VERSÕES DO CÓDIGO
- git reset --hard 2a31c00

COMO CRIAR BRANCHES
- git branch
- git branch stagin
- git checkout 'stagin'
- git push --set-upstream origin staging

GIT MERGE COMO UNIR O CÓDIGO 33min
- entrar na branch que vai receber a atualização
- quando entrar na branch principal puxar as atualizações da nuvem
- git pull
- git merge nomeDaBrach

1. git pull da branch principal
2. gerar uma nova branch a partir da branch principal
3. trabalhar e adicionar novas funcionalidades na nova branch
4. finalizar o trabalho na branch temporária
5. git checkout na branch principal
6. git pull
7. mergiar o código da branch temporária com a branch principal
8. git push da branch principal

CRIA UMA NOVA BRANCH COPIANDO A ATUAL
git checkout -b NomeDaBranch master

PULL REQUEST

GIT 	
touch .gitignore



git remote -v //mostra os repositórios remotos


