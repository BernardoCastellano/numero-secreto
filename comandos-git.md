# Comandos Git Terminal:

## Tipos de Git Log

+ **git log --help**
>Exibe um manual dos comandos e subcomandos, se digitar um comando e --help ele mostra como usa-lo, ex: git show --help mostra como usar esse comando

+ **git status**
>Mostra em qual brench o usuário está atualmente e se tem algo em haver para commitar

+ **git add .**
>Adiciona todos os arquivos alterados não commitados a um estado de pré-commit

+ **git commit -m "{mensagem}"**
>Commita os arquivos em estado de pré-commit passando uma mensagem dentro das aspas

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