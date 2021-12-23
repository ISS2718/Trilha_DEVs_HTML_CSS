# Iniciando no GIT (no terminal)

`git init <nome do diretório>`- inicia o repositório git

`git add <nome do arquivo>` - adiciona os arquivos para ratreio

`git commit –m <Adicionar qualquer mensagem sobre o commit aqui>` - faz um comit com dos arquivos rastreados com o add previamente

`git checkout -b <nome_da_branch>` - cria uma branch e troca para essa branch

`git checkout nome_da_branch` - se o nome da branch for substituido por master ele volta pra master

`git checkout <nome_da_branch>` - ele troca de branch e se o nome da branch for substituido por master ele volta pra master

`git merge <branch>` - fundi a branch atual com a \<branch> preservando a "cronologia"

`git rebase <branch>`- fundi copiando todos os commits da \<branch> atual para branch atual como se fossem novos commits (não preserva a "cronologia")
