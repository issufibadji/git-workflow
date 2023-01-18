# git_workflow
# git-workflow
## git local
-git init
-git status
-git add ola.txt
-git add .
-git rm ola.txt -f ->remover arquivo de forma forçada
-git rm nome-pasta/. -fr ->pagar tds arquivos dentro de diretorios
-f e r são usados quando arq não foi comitado
-git mv themes/test.txt ./ ->remover para arquivo da pasta
-git mv ola.txt hello.txt -> nomear arquivo
-git checkout -- test.txt -> remove as ultimas alteraçoes nos arquivos
-git commit -m"subindo arquivos"
## GitHub como Repositório
-cria repositorio 
- git remote add origin https://github.com/issufibadji/git_workflow.git
- git remote
- git remote -v ->Saber de mais detalhes
- git pull origin master  --allow-unrelated-histories ->sicroniaza com remoto
- git push --set-upstream origin master->subir
##  Trabalhando com Git Diff
- git log ->historio de commit
- git log -n 2-> listar dois ultimos commit
- git log --oneline
- git log --oneline -n 2
- git log --oneline
- git log --stat
- tecla Q para sair do formato git
- git log --oneline -n 2 --stat ->mesclar comandos
- git log --oneline --decorate 
- git log --oneline --decorate --parents ->mostra comite como o pai dele
- git diff ->mostra o arq original e arq modificado

----------------------------------------------------------------------
# resume
//Criar branch
git checkout -b novaBranch branchOrigem

//Limpar tudo
git clean -f

//Enviar nova branch pro repositório
git push --set-upstream origin nomeBranch

//Trocar de branch
git checkout nomeBranch

//Adicionar arquivos novos
git add [file]

//Adicionar todos os arquivos (cuidado!!)
git add *

//Commitar
git commit -am "TEXTO REFERENTE AO COMMIT"

//Atualizar branch
git pull

//Enviar pro git
git push

//Merge
git merge branchOrigem

//Reveter um commit que ainda não foi sincronizado
git reset --soft HEAD^

//Verificar status do git
git status

//Listar branchs locais
git branch

//Listar branchs do repositorio
git branch --all

//Abortar um merge
git merge --abort

//Discartar um arquivo
git checkout -- [file]

//Deletar branch local
git branch -D nomeBranch

//Deletar branch do repositorio
git branch -D -r origin/correcaoCobrancaPush

* limpar tudo
  git fetch origin
  git reset --hard origin/nomeBranch
  git pull



* Documentação
  https://education.github.com/git-cheat-sheet-education.pdf



---------------

deleta o repositorio q vc tem hj e clona via ssh

VERIFIQUE SE TEM ALGUMA COISA PRA PUBLICAR, VC VAI PERDER TUDO!!!!

1- deleta pelo smartgit
2- rm -rf cloud
3- git clone git@github.com:Superlogica/plataforma.git



