Aprendendo comandos do git e github

git init
- inicia novo projeto com git

git add <nome-arquivo>/.
-  add os arquivos que estão prontos para serem comitados

git commit -m "mensagem do commit"
- commit os arquivos do histórico

git log
- mosta os últimos comitts, log de alterações

git status
- como está o estado das nossas ramificações

git diff
- mostra o que foi alterado
- o que tem de alteração na ramificação

git merge
-merge de ramificações, mescla ramificações

git branch
- mostra a branch atual

git checkout <nome-branch>
- muda para essa branch

git checkout -b <nome-branch>
- cria uma nova branch a partir da atual

git remote add <nome> <url-repo>
- add um novo repositório remoto

git push <nome> <nome-da-branch>
- manda nossas alterações locais para o repositório remoto, pra cada branch

git pull <nome> <nome-da-branch>
- pega as alterações do repositório remoto, e manda pra nossa máquina

git fetch
- atualiza o novo histórico local de acordo com o histórico salvo lá no repositório
- sincronização do local com o remoto
