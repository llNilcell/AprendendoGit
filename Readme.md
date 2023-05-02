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

O proximo passo é enviar este folder para o github, porém, para isso, iremos precisar criar uma ponte entre o git bash e o github, para isso, iremos pegar o link do nosso repositorio no git hub, e no gitbash iremos escrever o seguinte comando:

git remote add "nome desejado", normalmente para a primeira conexão, utilização o nome "origin",  mas pode ser o nome que desejar, isso serve para voce criar uma conexão do seu gitbash com seu github, em seguida, damos o enter, e ele irá para a pagina de baixo sem nenhuma mensagem nova.

Em seguida, escreva git push -u "nome desejado" main, utilizado para empurrar "push" o arquivo para dentro do github, lembrando que cada conexão levará um nome diferente.

Vamos para a proxima fase, iremos realizar agora o versionamento, iremos realizar uma alteração no file e criar um novo file dentro do folder projeto git, a alteração, fica por sua conta, com o tempo, voce deverá realizar um novo codigo, ou corrigir algo, e irá utilizar o versionamento para enviar ao github novamente, então, vamos aprender está questão.
remos começar novamente pelos comandos do git, iniciando-se pelo git add, como neste momento temos mais de um arquivo, e imaginando que logo, estaremos com dezenas de arquivos abertos, não precisamos escrever um por um, podemos apenas colocar um ponto, desta forma, iremos estar selecionando todos as files juntas, então, o codigo ficará do seguinte jeito, git add .

Logo verá, que irá aparecer em verde que foi criado uma nova file em vermelho, os arquivos que foram modificados.
Depois deste passo, iremos utilizar o git commit -m "frase de sua preferencia" e dar o enter, lembrando que, a frase tem que ser objetiva para o proximo que ver o codigo, ou até mesmo voce, poder entender o que foi modificado.
