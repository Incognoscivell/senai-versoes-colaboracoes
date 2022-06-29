# senai-versoes-colaboracoes
Repositório de versões e colaborações

Readme de exemplo

lembrei do comando: git commit

![image](https://user-images.githubusercontent.com/90740731/175144118-e5f7dda9-533e-4dde-b5e6-45da93020f29.png)

Comandos realizados:

1º Comando: git init
Para iniciar um repositório na pasta desejada, ou simplesmente abrir o Git Bash dentro da própria pasta em sua interface.


2º Criar um arquivo de texto dentro da pasta.
Clicar com o botão direito do mouse, escolher novo e arquivo de texto.


3º Comando: git status 
Para rastrear alterações em arquivos dentro do repositório


4º Comando: git add nome_do_arquivo
O comando git add [nome-do-arquivo] adiciona os arquivos modificados na área de staging, que é um ponto intermediário entre a máquina do desenvolvedor e o repositório de trabalho. A staging é uma área que você pode fazer uma revisão do que foi alterado antes de ser salvo no histórico de alterações.


5º Comando: git status 
Para rastrear alterações em arquivos dentro do repositório


6º Comando: git commit -m "meu primeiro commit" (ou o que quiser comentar a respeito)


7º Comando: git log
Para visualizar as alterações através dos commits.


8º Etapa e comandos: git remote add origin git@github.com:[endereço].git

![image](https://user-images.githubusercontent.com/90740731/175159775-21127ca9-c268-4d46-9d61-fdb07b21ddf6.png)

Depois de criar o repositório remoto, precisamos fazer a ligação com o repositório local. 


9º Comando: git remote –v
Para visualizar o repositório remoto


10º Comando: git pull
Para baixar a alteração no repositório remoto


11º Comando: git push -u origin master
Publicar as alterações no repositório remoto, e no repositório remoto, vamos autorizar o usuário.

Depois, vamos verificar se todas as etapas foram completadas corretamente, então, devemos:
 -> no repositório local: visualizar a autenticação de usuário feita no repositório remoto;
 -> no repositório remoto: visualizar a publicação feita.
