Olá estou aprendendo a utilizar o git
Passo a passo para aprender a usar o Git

Primeiro, abra o Git Bash;

Digite git --version, para apenas validar a versão do git (Levarei isso como uma oração sempre que abrir o git pela primeira vez em um equipamento/projeto), em seguida, feche-o,

Segundo, crie uma pasta na area de trabalho com um titulo que defina o projeto que irá iniciar e dentro desta pasta, clique com o botão direito e selecione a opção "Abrir com o code", ele abrirá o VSCode,e está com a pasta que voce criou aberto.

Terceiro, dentro deste folder(pasta) aberto no VSCode, crie um arquivo chamado Readme.md, e nele escreva uma frase, de sua escolha.

Quarto, abra o folder que criou na area de trabalho e verá que o arquivo que criou no VSCode estará aparecendo lá, com o botão direito selecione a opção "Git Bash Here",
Ele abrirá o Git Bash desta vez, direcionado para um git do arquivo que criou no VSCode.

Quinto, vamos começar os codigos no Git,

Digite, git init e em seguida digite git add e de o enter, e o nome do arquivo que criou, então ficará assim "git add Readme.md"

Em seguida voce verá que irá aparecer um (master) na proxima linha escrita, o que significa que a partir de agora está atuando no arquivo citado antes.

Sexto, digite git status e de o enter, e voce verá que ele vai apresentar os arquivos que ainda não enviados e guardados, o comando que faz está ação é conhecido como commit, então este será o proximo passo.

Sétimo, digite git commit -m "Texto de sua escolha" e de o enter, em seguida digite git status e de o enter, verá que todos os arquivos disponiveis para serer enviados e guardados já fizeram está ação, e não tem mais nada disponivel para "commitar".

Muitas empresas utilizam o MAIN inves do MASTER, e iremos alterar esse nome também, é simples,

Digite git branch -M "main" e de o enter, desta forma o nome mudará de MASTER  para MAIN.