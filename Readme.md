arquivos md (mark down), são um modelo padrão para arquivos do tipo leia-me.
Esse arquivo tem apenas algumas instruções de uso relacionadas ao projeto.

Uma dica importante sobre o uso do git é que se você estiver na pasta em que deseja criar um git, basta clicar com o botão direito e então escolher a opção git bash here.
O bash do git será aberto nessa pasta e será possível ter um ganho de produtividade interessante.

Depois de abrir esse git bash, basta utilizar o comando git init e será criado o branch master nessa pasta.

Na pasta .git (que fica oculta), ficam contidas todas as modificações que são feitas no git.

Alguns git podem mudar o branch principal de master para main

É uma questão opcional
//aqui está sendo modificado de master para main
git branch -M "main"

Ha interfaces do git que podem ajudar.
Foi apresentado o Gui Client, mas não foi utilizado.

Para ter uma lista dos branchs do seu projeto:
git branch --list
-----------------------------------------------------------------------
Após essa parte foi acessado github

é necessário digitar o seguinte comando
//Essa parte do link é obtida no próprio github
//assim que o novo repositório é criado lá

git remote add origin https://github.com/PinguinBarbudo/GitFafBalle.git

Esse comando ira adicionar o comando remote como o diretório remoto no github em que o arquivo será espelhado.
Em seguida é só digitar o comando a seguir para enviar os seus arquivos para o github
git push -u origin main

Após digitar esse código, será aberta uma aba de login em que será possível autenticar o repositório

Com essas modificações, será possível espelhar os commits no repositório do github.
Para tal, basta apenas fazer os commits normalmente e depois de concluir todo o processo, basta digitar os seguinte comando:

git push origin main

Assim as modificações serão adicionadas no repositório do github.