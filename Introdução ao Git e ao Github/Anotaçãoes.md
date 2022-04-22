# **Comandos Git** :mortar_board: :computer: :pushpin: :recycle: :boom: :running::dash: :rocket: :green_book: :coffee:

![Alt ou título da imagem](https://git-scm.com/images/logo@2x.png) 
### *Segue abaixo alguns comandos de git com os comentário de cada um, criei alguns script em algumas linguagens tranzendo os comandos específicos por :video_game: diversão :roller_coaster: e treinamento:rocket:*

## *Create* :white_check_mark:


Commands  | Functions
--------- | ------
git clone htts://repositorio.git | Copiando repositório
git init | Criando reposiótorio local

listando em markdown

## *Local changes* :white_check_mark:

Script HTML
~~~html

<!DOCTYPE html>
<html lang="pt-br">
 <head>
  <!--Mostrando arquivos alterados no repositório-->
  <title>git status</title>
 </head>
 <body>
   <!--changes em arquivos rastreados-->
   <p>git diff</p>
   <!-- Add all changes atuais para o proximo commit -->
   <p> git add .</p>
   <!-- Add some changes em <file>-->
   <p> git add . -p <file></p>
   <!--  Confirma todas as local changes em arquivos rastreaveis <file>-->
   <p> git commit -a</p>
   <!-- Confirma changes previamente preparadas <file>-->
   <p> git commit </p>
   <!-- Mudando ultimo commit <file>-->
   <p> git commit --amend</p>
   
 </body>
</html>
~~~


## *Histórico* :white_check_mark:

Script JavaScript
~~~~javascript
 let text1 = " git log "; // Mostrando todos os commit desde o atual
 
 let text2 = " git log -p <file> "; // Mostrando mudanças ao logo do arquivo
 
 let text3 = " git blame <file> "; //Mostrando alterações realizadas pelos dev, o quê e quando <file>

~~~~

## *Branches* :white_check_mark:

Script PHP
~~~php
<?php
// Um array bidimensional
$commands=array
  (
  // listando todos os ramos existentes
  array("git branch -av",100,96),
  // mudar ramo head
  array("git checkout <branch>",60,59),
  // criando uma nova filial com base
  array("git checkout <new-branch>",110,100),
  // criando uma nova filial com base
  array("git checkout <new-branch>",110,100),
  // criando uma nova filial com base
  array("git checkout--track <remote/branch>",110,100),
  // delete filial local
  array("git branch -d <branch>",110,100),
  // commit com tag
  array("git tag <tag-name>",110,100)
  );

?>
~~~
## *Atualizar/publicar* :white_check_mark:

Script Java
~~~java
public class Commands {
  public static void commands(String[] args) {
    System.out.println("git remote -v"); //Lista todos os controles remotos configurados atualmente
    System.out.println("git remote show <remote>"); //Mostra informações sobre um controle remoto 
    System.out.println("git remote -v"); //Add um novo repositório remoto,denominado <remote>
    System.out.println("git remote add <shortname> <url>"); //Lista todos os controles remotos configurados atualmente
    System.out.println("git fetch <remote>"); //Baixa alterações de <remote>, mas não integre no HEAD
    System.out.println("git pull <remote> <branch>"); //Baixa alterações e marque / integre diretamenta no HEAD
    System.out.println("git push <remote> <branch>"); //Publique as alterações locais remotamente
    System.out.println("git branch -dh <remote/branch>"); //Excluindo uma filial no controle remoto
    System.out.println("git push --tags"); //Publicar Tags
  }
}
~~~
## Merge & Rebase :white_check_mark:

Script Python
~~~python
#Merge <branch> em seu HEAD atual
a = "git merge <branch>"
print(a)

#Rebase seu HEAD atual <branch>
a = "git rebase <branch>"
print(a)

#Abortar um rebase
a = "git rebase --abort"
print(a)

#Continuar Rebase após solucionar conflitos
a = "git rebase --continue"
print(a)

#ferramenta de fusão configurada do tour para solucionar conflito
a = "git mergetool"
print(a)

#editor de tour para solucionar conflitos manualmente e após solucionar marca o arquivo resolved-file
a = "git add <resolved-file>"
b = "git rm <resolved-file>"
print(a)
print(b)

~~~

## *Reset * :white_check_mark:

Script SQL
~~~sql
/*descarte todas as mudanças em seu diretório*/
SELECT git reset -hard HEAD FROM Commands;

/*descarta alterações locais em arquivo especifico*/
SELECT git checkout HEAD <file> FROM Commands;

/*reverte um commit*/
SELECT git revert <commit> HEAD FROM Commands;

/*redefina o HEAD para um commit anterior e descarta todas alterações */
SELECT git reset -hard <commit> FROM Commands;

/*preservar todas mudanças*/
SELECT git reset <commit> FROM Commands;

/*preservar mudanças locais*/
SELECT git reset -keep <commit> FROM Commands;
~~~
