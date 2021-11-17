Primeiro arquivo do projeto

Comandos:

git init

git commit -m "Add readme.md"

git config --global user.email jorgegfrc@gmail.com

git config --global user.name jorgegfrc01

git status

git add readme.md 

git commit -m "comentario: Add readme.md"

git log --author="j" (pesquisa por autor)

git shortlog (mostra em ordem afabetica)

git shortlog -sn (mostra a quantidade de commit por autor)

git log --graph (mostra o log de forma grafica)

git show c0030ab17b0bd872dae0ba6cd17255bb2252adaa

git diff (mostra as modificacoes do arquivo)

git diff --name-only (mostra somente o nome do arquivo modificado)

git checkout readme.md (modifica o arquivo para um estado anterior)

git reset HEAD readme.md (volta o arquivo que ja foi add para o estado anterior)

git reset --soft (volta o arquivo do commit mas fica pronto para o commit)

git reset --mixed (volta o arquivo do commit e modifica o arquivo)

git reset --hard (volta o arquivo do commit ignorando tudo o que foi feito nele)


