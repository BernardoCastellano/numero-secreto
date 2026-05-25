# Comandos Git Terminal:

+ **git log --help**
>Exibe um manual dos comandos e subcomandos, se digitar um comando e --help ele mostra como usa-lo, ex: git show --help mostra como usar esse comando

+ **git status**
>Mostra em qual brench o usuário está atualmente e se tem algo em haver para commitar

+ **git add .**
>Adiciona todos os arquivos alterados não commitados a um estado de pré-commit

+ **git commit -m "{mensagem}"**
>Commita os arquivos em estado de pré-commit passando uma mensagem dentro das aspas, os commits sempre passam para a brench master/main quando não especificada a branch

+ **git log**
>Mostra todos os commits, a mensagem, a data e quem comitou;

+ **git log --oneline**
>Mostra todos os commits de maneira resumida (id do comit e a mensagem);

+ **git log -p**
>Mostra os todos os dados do commit, quem comitou, a data, o que alterou, a mensagem, etc...

+ **git log --graph**
>Mostra uma linha do tempo dos commits, saindo do inico para a linha atual

+ **git log --pretty** ou git **log --format**
>Exibe o commit de forma personalizada, permitindo escolhar as informações a serem exibidas

+ **git show {hash do commit}**
>Exibe as informações commit especfico passando o hash unico dele, se digitar somente git show sem o hash ele mostra o commit HEAD, ou seja, ele mostra somente o ultimo commit enviado

+ **git diff**
>Mostra a diferença entre dois estados, o ultimo commitado (HEAD) e o que foi alterado mas não commitado. Se passar dois hashs pode-se ver a diferença entre os dois commits, ex: git diff xxxxxxxx..yyyyyyy

+ **git push {local}**
>Manda as informações alteradas para um local específico sem precisar de sync changes

+ **git pull**
>Recebe as ultimas alerações do repósitório online, ultilizando merge ele mescla as alterações do repositório com as informações locais, sem o uso do merge ele substitui 100% do código 

+ **git branch**
>Mostra os 'galhos' do repositório, as ramificações

+ **git branch {nome}**
>Adiciona uma branch nova passando um nome para ela

+ **git branch -d {nome}**
>Remove uma branch específica passando o nome dela, não se pode remover a branch onde você está

+ **git checkout {branch} ou git switch {branch}**
>Conecta o usuário a branch selecionada, torna essa a branch utilizada por ele

+ **git checkout -b {branch} ou git switch -c {branch}**
>Cria e conecta o usuário a branch criada

+ **git merge {branch}**
>Mescla a brench atual com a branch selecionada, alterando os arquivos mexidos na branch selecionada

+ **git rebase {branch}**
>Reescreve a historia dos commits, pega todos os commits da branch selecionada e adiciona 1 a 1 na branch atual, deixa eles na frete dos commits da branch atual 

+ **git stash**
>Guarda o que não foi commitado ou stashado em um estoque, adiciona as modificações em pilha 

+ **git stash apply {id}**
>Aplica somente a stash com o id inserido

+ **git stash pop**
>Aplica o que estiver no estoque, sempre pega a ultima stash

+ **git stash list**
>Lista tudo o que estiver em estoque

+ **git stash clear**
>Limpa o estoque 

+ **git stash push -m "{mensagem}"**
>Guarda algo no stash com uma mensagemf