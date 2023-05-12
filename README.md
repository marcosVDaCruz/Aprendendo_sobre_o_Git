# Estou aprendendo sobre o Git aqui.

## Notas:
  Antes de tudo no Git Bash use o comando $ git config --global user.name "seu nome ou nick", para ter o nome do usuario atual, junto do comando $ git config --global user.email "seu email", para ter o email do usuario atual, esses dados podem ser vistos se você abrir o Git GUI, onde o vai aparecer qual usuario vez tal alteração e tals.

  Primeiramente deve-se criar o repositorio com o comando $ git init, assim temos um repositorio onde o codigo pode ser armazenado, para criar um tipo de link entre o repositprio local(PC) e o remoto(Github) deve-se usar o comando $ git remote add "nome curto" "url", sendo o "nome curto" de sua escolha e o "url" aquele que você pode adquirir criando um repositorio no Github.

  Da pra imaginar o Git como um palco junto dos bastidores, tudo que esta no palco pode ser enviado para o Github, ja oque esta nos bastidores deve ir para o palco para ser enviado usando o $ git add "arquivo", e logo depois usando o $ git commit -m "Comentario", assim oque esta agora no palco pode ser enviado para o Github atravez do comando $ git push.
  Exemplo:
    $ git status (Aqui você pode ver qual arquivo foi modificado ou é novo para enviar pro palco.)
    $ git add "nome do arquivo" (Aqui você seleciona qual arquivo quer preparar para o palco.)
    $ git commit -m "Comentario" (Aqui os arquivos selecionados dos bastidores vão para o palco.)
    $ git push (Aqui tudo que estava ja no palco vai para o Github.)

## Comandos:
  $ git --version (mostra a versão atual do Git);
  $ git status (mostra o status do repositorio);
  $ git branch -m "Novo nome da branch" (Comando para renomear a branch, colocar novo nome entre aspas);

### git config
  $ git config --global user.name "seu nome" (Configura seu nome de usuario);
  $ git config --global user.email "seu email" (Configura seu email de usuario);

### git init (Cria um repositorio novo em branco, apartir daqui sera possivel armazenar o codigo);
  $ git init "Nome do Repositorio" (Cria um repositorio com um nome especifico);

### git clone (Cria uma copia exata de um repositorio ja existente);

### git add (Adiciona arquivos especificados de codigo ao seu repositorio, sejam novos ou anteriores que foram editados, esse comando oferece difrentes possibilidades de sintaxe);
  $ git add "seu arquivo" (Esse comando ira adicionar o arquivo em especifico ao seu repositorio);
  $ git add * (Esse comando ira adicionar todos os arquivos novos e/ou modificados ao repositorio);

### git commit

Estudei ate aqui, agora to com preguiça, estudo mais amanha.
