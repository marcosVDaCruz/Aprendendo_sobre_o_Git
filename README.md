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
Mostra a versão atual do Git:

    $ git --version

Mostra o status do repositorio:

    $ git status

Comando para renomear a branch, colocar novo nome entre aspas:

    $ git branch -m "Novo nome da branch"

### git config
Configura seu nome de usuario:
    $ git config --global user.name "seu nome"
Configura seu email de usuario:
    $ git config --global user.email "seu email"

### git init
Cria um repositorio novo em branco, apartir daqui sera possivel armazenar o codigo:
    $ git init
Cria um repositorio com um nome especifico:
    $ git init "Nome do Repositorio"

### git clone
Cria uma copia exata de um repositorio ja existente e executa um **$ git init** internamente e verifica todo o conteudo do projeto:
    $ git clone "url do projeto"

### git add
Adiciona arquivos especificados de codigo ao seu repositorio, sejam novos ou anteriores que foram editados, esse comando oferece difrentes possibilidades de sintaxe:
-Esse comando ira adicionar o arquivo em especifico ao seu repositorio:
    $ git add "seu arquivo"
-Esse comando ira adicionar todos os arquivos novos e/ou modificados ao repositorio:
    $ git add *

### git commit
Armazena o conteúdo atual do índice em um novo commit, juntamente com uma mensagem de registro do usuário que descreve as mudanças.
Se usa o commit depois de já ter feito o git add, para fazer o commit:
    $ git commit -m "comentario"



Estudei ate aqui, agora to com preguiça, estudo mais amanha.
