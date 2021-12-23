# Iniciando no GIT (no terminal)

`git init <nome do diretório>`- inicia o repositório git

`git add <nome do arquivo>` - adiciona os arquivos para ratreio
* `git add .` - adiciona tudo da pasta raiz do repositóirio

`git commit –m <Adicionar qualquer mensagem sobre o commit aqui>` - faz um comit com dos arquivos rastreados com o add previamente

`git checkout -b <nome_da_branch>` - cria uma branch e troca para essa branch

`git checkout nome_da_branch` - se o nome da branch for substituido por master ele volta pra master

`git checkout <nome_da_branch>` - ele troca de branch e se o nome da branch for substituido por master ele volta pra master

`git merge <branch>` - fundi a branch atual com a \<branch> preservando a "cronologia"

`git rebase <branch>`- fundi copiando todos os commits da \<branch> atual para branch atual como se fossem novos commits (não preserva a "cronologia")

`git clone <url do repositório>` - clona um repositório a partir de uma URL

`git fetch` - atualiza o repositório local com o repositório remoto baixando todos os commits novos do remoto para o local

`git pull` - atualiza o repositório local com o repositório remoto como o `git fetch`, mas realiza um merge da usa branch atual com a equivalente do remoto.

`git push` - atualiza o repositório remoto com as mudanças do repositório local
* cada branch deve ser confgurada individualmente como uma branch remota  com: `git push -u origin <branch>`