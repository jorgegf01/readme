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

git reset --soft +codigo hash (volta o arquivo do commit mas fica pronto para o commit)

git reset --mixed +codigo hash(volta o arquivo do commit e modifica o arquivo)

git reset --hard +codigo hash(volta o arquivo do commit ignorando tudo o que foi feito nele)

Exemplo:
git reset --soft 206f669ed5e7d6aa787980a26d04a7de972ff22

Gerar chave ssh:
ssh-keygen -t rsa -b 4096 -C "jorgegfrc@gmail.com"

Adicionar no github:

https://github.com/settings/keys

ver o remote na maquina:
git remote -v

remover o remote:
git remote remove origin

adicionar remote:
git remote add origin git@github.com:jorgegf01/readme.git

git branch -M main

Enviar para o github:
git branch -M main

Criar um branch:
git branch teste

mudar de branch:
git checkout teste

deletar um branch:
git branch -D teste

uniao dos branches:


Criando o .gitignore

Exemplo: cria o arquivo .gitignore e escreve *.json

Git stash
grava o arquivo em uma pasta que e chamado quando necessario
git stash apply (para salvar as mudancas)


alias:
cria apelidos para os comandos
exemplo:
git config --global alias.s status (cria o apelido s para o comando status)

tag:
git tag -a 1.0.0.0 -m "readme.md finalizado"

git push origin main --tags

git revert (reverte um commit)

apagar uma tag no github:
git push oringin :1.0.0

apagar um branch no github:
git push oringin :nome_da_branch