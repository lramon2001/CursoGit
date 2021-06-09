# Curso Git

### git init : inicializa um repositorio
### git status : verifica os status dos arquivos no diretorio em que está o repositório 
### git commit -m "comentário" : realiza o commit
### git config --global user.name "seu nome" 
### git config --global user.email "seu email"
### git revert hashDoCommit : desfaz um commit
### git push -u origin main : envia o arquivo com o log de commits assim como os arquivos adiconados ao commit para o repositório remoto
### git pull origin master : adiciona ao repositório local as alterações presentes no repositório remoto
### git branch nomeDaBranch : cria nova branch 
### git switch nomeDaBrannch : troca para a branch requerida
### git fetch :  traz do repositório remoto todas informações sobre ele que ainda não estão no seu repositório local. Um detalhe muito importante: o comando git fetch NÃO incorpora essas mudanças, ou seja não realiza um merge
### git merge: mescla as branches
### git checkout: Além de mudar de branch, o git checkout pode ser usado para voltar um determinado arquivo para seu estado na staged area. A staged area são os arquivos que estão prontos para serem comitados. Em outras palavras, são os arquivos que executamos o comando git add 
