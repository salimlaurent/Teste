$meu projeto teste

git init
- iniciar novo projeto com git

git add <nome-arquivo> | .(todos arquivos)
- add os arquivos que estão prontos para serem commitados

git commit -m "mensagem commit"
- commit os arquivos no historico

git log
- mostra os ultimos commit, log de alterações

git status
- como está o estado das nossas ramificações

git diff
- que mostra o que foi alterado
- o que tem de alteração na ramificação

git merge
- mescla ramificações

git branch
- motra a branch atual

git checkout <nome-branch>
- muda de branch

git checkout -b <nome-da-nova-branch>
- cria uma nova branch

git remote add <nome> <url>
- add um novo repositorio remoto

git push <nome> <nome-da-branch>
- manda nossas alterações locais para o repositório remoto, para cada branch

git pull <nome> <nome-da-branch>
- pega as alterações do repositório remoto, e joga pra nossa maquina

git fetch
- atualiza o novo histórico local de acordo com o histórico salvo no repositorio
- sincronização do local com o remoto