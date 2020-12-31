1 - git init - criar um repositório
2 - git status - ver as alterações
3 - git add arquivo.txt
4 - git log - ver o histório
5 - git checkout a3232323  - volar os dados a um determinado ponto
6 - git checkout master - voltar a última alteração
7 - git branch nome_do_ramo - criar um ramo
8 - git checkout nome_do_ramo - vai pular para o ramo criado
9 - git merge nome_do_ramo - vai integrar o ramo no master
10 - git branch -D nome_do_ramo - vai deletar o ramo
11 - git reflog - mostra todos os commits mesmo os desanexados ### https://git.seveas.net/recovering-from-a-detached-head.html
12 - git commit --amend - este comando tem por função alterar o último commit feito.
13 - git checkout -b nomedobranch <sha1 do primeiro commit> # Cria novo branch apontando para o primeiro commit
14 - git reset - remove arquivo do stage (depois do add )
15 - git init --bare #compartilhamento offline (cria um repositorio offline como se fosse remoto)
     git remote add usb E:\meu-projeto	
16 - git rm -r --cached obj\Debug - remove os arquivos depois de estar commitados	
17 - git rm -r --cached . && git add . && git commit -m ".gitignore fix" - Removendo arquivos rastreados no seu repositório git baseado no .gitignore 
		https://medium.com/@chroda/removendo-arquivos-rastreados-no-seu-reposit%C3%B3rio-git-baseado-no-gitignore-844ce2d6dc56
18 - git clean  -d  -fx #remove arquivos do working dir, antes do add. o x faz remover arquivos ignorados tbm.
---------------------------------------------------------------REMOTO GIT HUB---------------------------------------------
1 - git remote add origin https://github.com/eurismarsaib/teste_git.git (origin é o nome para o ponto remoto)
2 - git push origin master - envia para o repositório remoto a branch master
3 - git remote -v - lista as url's
4 - git clone https://github.com/eurismarsaib/teste_git.git pasta - clona o repositorio remoto para a pasta
5 - git pull origin master - puxa as alterações remotas do origin para minha master local
