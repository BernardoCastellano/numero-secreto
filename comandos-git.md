# Comandos Git Terminal:

## Tipos de Git Log
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

+ **git log --help**
>Exibe um manual dos comandos e subcomandos, se digitar um comando e --help ele mostra como usa-lo, ex: git show --help mostra como usar esse comando

+ **git show {hash do commit}**
>Exibe as informações commit especfico passando o hash unico dele, se digitar somente git show sem o hash ele mostra o commit HEAD, ou seja, ele mostra somente o ultimo commit enviado