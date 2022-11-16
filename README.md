# Projeto: Primeiro repositório no GitHub :call_me_hand:

Projeto com intuito de colocar em prática os conhecimentos básicos sobre sistemas de versionamento de código, a fim de aplicar o que foi visto na etapa de _conhecimentos básicos sobre Git e GitHub_.

#### Etapas 

- Criar uma pasta para a DIO, na qual serão separados os conteúdos por curso (neste caso, foi criada uma pasta para a Orange Tech) e dentro da pasta do curso, uma pasta do desafio, na qual está alocada este README;

- Posteriormente, foi aberto o 'Git Bash' diretamente da pasta. Aberto o CLI, foi executado o comando _git init_ para criar um repositótio;

- Em seguida, um _git status_ para verificar os arquivos do repositório e este arquivo README estava como 'untracked'. Para seguir, foi preciso salvar este arquivo e executar um _git add *_ para o git poder rastreá-lo;

- Uma vez rastreado, para registrar tudo o que foi feito até o momento, foi necessário executar o _git commit -m "Primeiro commit"_ para salvar as alterações e descrever o o que foi feito nesta versão do projeto;

- Feito o commit, o passo seguinte foi ir até ao GitHub e criar o repositório para poder receber o que foi feito até então na máquina local. Então dirigindo até o '+' no canto superior direito e clicando em 'New Repository' é possível acessar a tela para dar um nome, uma descrição, definir o repositório como público e criar devidamente;

- Criado o repositório, bastou copiar o link e voltar para o git e executar o comando _git remote add origin https://github.com/VsimonSD/projeto-primeiro-repositorio.git_ para o repositório local alcançar o repositório remoto no GitHub. Acionamos o repositório local com o _git remote_ e atribuímos um 'alias' ao link do nosso repositório como o _add origin_ e atribuindo o link em seguida. Assim, sempre que referenciarmos o 'origin', estaremos nos referenciando ao nosso repositório;

- Para subir o que fora feito na máquina local, bastou executar o _git push origin master_ para "empurrar" nossas alterações para o repositório remoto no GitHub e 'voi lá':

  ![image-20221116084245291](C:\Users\vitus\AppData\Roaming\Typora\typora-user-images\image-20221116084245291.png)

  

- Feito tudo isto, falta subir as atualizações efetuadas neste README para o GitHub. Para seguir, serão repetidas partes do processo;

- Primeiro: este arquivo será salvo novamente;

- Segundo: será executado um _git status_ para verificar os arquivos que ainda não foram trackeados pelo Git;

- Terceiro: será executado um _git add *_ em seguida para que os arquivos alterados sejam treckeados pelo Git;

- Quarto: para salvar, é necessário executar um _git commit -m "Commit de atualizacao"_ para que o Git armazene todas as alterações efetuadas;

- Quinto: Executar o _git push origin master_ para subir até o GitHub todas as alterações efetuadas.



Voi lá!  :) 