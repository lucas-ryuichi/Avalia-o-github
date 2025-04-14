# Avalia-o-github
repositorio criado para usar na prova 


## Atividade Avaliativa - Git Colaborativo com Portugol

## Integrantes do grupo
- Lucas Ryuiti Hashimoto Arruda
- Vitor Sence Botelho Manhas 
- LucaS da Silva Rocha

  ## Objetivo
Desenvolver colaborativamente um algoritmo em Portugol de avaliação notas 


## Etapas realizadas por cada membro

### Lucas Ryuiti Hashimoto Arruda 
- Como criei o repositório ?
- Criei através do próprio github e convidei os colegas através do próprio github
- Como Configurou o Git? não deixe exposto sua chave.
- compuni@maker26 MINGW64 ~
$ git config --global --unset user.name

compuni@maker26 MINGW64 ~
$ git config --global --unset user.email

compuni@maker26 MINGW64 ~
$ rm -f ~/.ssh/id_rsa*

compuni@maker26 MINGW64 ~
$ git config --global user.name "lucas ryuichi"

compuni@maker26 MINGW64 ~
$ git config --global user.email "ryuitilucas9@gmail.com"

- Criou o arquivo `algoritmo.por` com a estrutura inicial:
- programa {
  funcao inicio() {
- fez o que? depois?...
-  real n1




    escreva("Digite sua nota: ")
    leia(n1)




    se (n1>=9 e n1<=10) {
      escreva("Excelente - nota A")
     
    } senao {
      se (n1>=7 e n1<=8.9)
    escreva("Bom - nota B")

### Lucas da Silva Rocha
- Como Configurou o Git:
  
compuni@maker313 MINGW64 ~
$ git config --global user.name

compuni@maker313 MINGW64 ~
$ git config --global --unset user.name

compuni@maker313 MINGW64 ~
$ git config --global --unset user.email

compuni@maker313 MINGW64 ~
$ rm -f ~/.ssh/id_rsa*

compuni@maker313 MINGW64 ~
$ git config --global user.name "Masterlu22"

compuni@maker313 MINGW64 ~
$ git config --global user.email "lucasrochanilo@gmail.com"

- Fez `git pull` após o commit de:
   Lucas Ryuiti.
  
- Adicionou lógica de
    senao se( n1 >= 5 e n1 <= 6.9){
    	escreva(" Regular - nota C")

### Vitor Sence Botelho Manhas
- Como Configurou o Git? não deixe exposto sua chave.
- Meu gitBash ja está configurado pois estou usando o meu computador pessoal.
- Fez `git pull` após o commit de Lucas da Silva.
- Finalizou o algoritmo com lógica . . .
- senao
    	se (n1>=3 e n1<=4.9)
    	escreva("Insuficiente - nota D")
    	senao
    	se (n1>=0 e n1<=2.9)
    	escreva("Reprovado - nota E")
    }

  }
    }


  ## Comandos utilizados
Todos os comandos foram executados via terminal utilizando chave SSH:
### Comandos de Lucas Ryuiti:
compuni@maker26 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 791

compuni@maker26 MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (ryuitilucas9@gmail.com)

compuni@maker26 MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

compuni@maker26 MINGW64 ~
$ ssh -T git@github.com
git@github.com: Permission denied (publickey).

compuni@maker26 MINGW64 ~
$ ssh -T git@github.com
git@github.com: Permission denied (publickey).

compuni@maker26 MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

compuni@maker26 MINGW64 ~
$ ssh -T git@github.com
Hi lucas-ryuichi! You've successfully authenticated, but GitHub does not provide shell access.

compuni@maker26 MINGW64 ~
$ git clone git@github.com:lucas-ryuichi/Avalia-o-github.git
Cloning into 'Avalia-o-github'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

compuni@maker26 MINGW64 ~
$ cd repositorio
bash: cd: repositorio: No such file or directory

compuni@maker26 MINGW64 ~
$ cd ~/Desktop

compuni@maker26 MINGW64 ~/Desktop
$ cd Avalia-o-github
bash: cd: Avalia-o-github: No such file or directory

compuni@maker26 MINGW64 ~/Desktop
$ cd repositorio
bash: cd: repositorio: No such file or directory

compuni@maker26 MINGW64 ~/Desktop
$ cd Avalia o github
bash: cd: too many arguments

compuni@maker26 MINGW64 ~/Desktop
$ cd Avalia-o-github
bash: cd: Avalia-o-github: No such file or directory

compuni@maker26 MINGW64 ~/Desktop
$ git clone git@github.com:lucas-ryuichi/Avalia-o-github.git
Cloning into 'Avalia-o-github'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

compuni@maker26 MINGW64 ~/Desktop
$ cd Avalia-o-github

compuni@maker26 MINGW64 ~/Desktop/Avalia-o-github (main)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

compuni@maker26 MINGW64 ~/Desktop/Avalia-o-github (main)
$ git add .

compuni@maker26 MINGW64 ~/Desktop/Avalia-o-github (main)
$ git commit -m "Primeira parte do código"
[main 760e7bb] Primeira parte do código
 1 file changed, 20 insertions(+), 1 deletion(-)

compuni@maker26 MINGW64 ~/Desktop/Avalia-o-github (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 446 bytes | 446.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:lucas-ryuichi/Avalia-o-github.git
   00bfbf8..760e7bb  main -> main

   ## Comandos de Lucas da Silva Rocha:
    compuni@maker313 MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 569

compuni@maker313 MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/compuni/.ssh/id_rsa (lucasrochanilo@gmail.com)

compuni@maker313 MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

compuni@maker313 MINGW64 ~
$ ssh -T git@github.com
Hi Masterlu22! You've successfully authenticated, but GitHub does not provide shell access.

compuni@maker313 MINGW64 ~
$  git clone git@github.com:lucas-ryuichi/Avalia-o-github.git
Cloning into 'Avalia-o-github'...
remote: Enumerating objects: 6, done.
remote: Counting objects: 100% (6/6), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 6 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (6/6), done.

compuni@maker313 MINGW64 ~
$ cd ~/Desktop

compuni@maker313 MINGW64 ~/Desktop
$ cd Avalia-o-github
bash: cd: Avalia-o-github: No such file or directory

compuni@maker313 MINGW64 ~/Desktop
$ cd Avalia-o-github
bash: cd: Avalia-o-github: No such file or directory

compuni@maker313 MINGW64 ~/Desktop
$ cd Avalia-o-github
bash: cd: Avalia-o-github: No such file or directory

compuni@maker313 MINGW64 ~/Desktop
$ git clone git@github.com:lucas-ryuichi/Avalia-o-github.git
Cloning into 'Avalia-o-github'...
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 9 (delta 0), reused 3 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (9/9), done.

compuni@maker313 MINGW64 ~/Desktop
$ cd Avalia-o-github

compuni@maker313 MINGW64 ~/Desktop/Avalia-o-github (main)
$ git pull
Already up to date.

compuni@maker313 MINGW64 ~/Desktop/Avalia-o-github (main)
$ git add .
warning: LF will be replaced by CRLF in portugol.por.
The file will have its original line endings in your working directory

compuni@maker313 MINGW64 ~/Desktop/Avalia-o-github (main)
$ git push
Everything up-to-date

compuni@maker313 MINGW64 ~/Desktop/Avalia-o-github (main)
$ git commit -m "Descrição da alteração"
[main 570f31c] Descrição da alteração
 1 file changed, 16 insertions(+), 2 deletions(-)

compuni@maker313 MINGW64 ~/Desktop/Avalia-o-github (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 12 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 728 bytes | 728.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To github.com:lucas-ryuichi/Avalia-o-github.git
   760e7bb..570f31c  main -> main

compuni@maker313 MINGW64 ~/Desktop/Avalia-o-github (main)
$

   

compuni@maker26 MINGW64 ~/Desktop/Avalia-o-github (main)
$


  
### Comandos Vitor Sence Botelho Manhas

vitor@V▒tor MINGW64 ~
$ eval "$(ssh-agent -s)"
Agent pid 1838

vitor@V▒tor MINGW64 ~
$ ssh-add ~/.ssh/id_rsa
Identity added: /c/Users/vitor/.ssh/id_rsa (vitor.manhas@edu.unifil.br)

vitor@V▒tor MINGW64 ~
$ clip < ~/.ssh/id_rsa.pub

vitor@V▒tor MINGW64 ~
$ ssh -T git@github.com
Hi vitorsence! You've successfully authenticated, but GitHub does not provide shell access.

vitor@V▒tor MINGW64 ~
$ git pull
fatal: not a git repository (or any of the parent directories): .git

vitor@V▒tor MINGW64 ~
$ git clone git@github.com:lucas-ryuichi/Avalia-o-github.git
Cloning into 'Avalia-o-github'...
remote: Enumerating objects: 9, done.
remote: Counting objects: 100% (9/9), done.
remote: Compressing objects: 100% (7/7), done.
remote: Total 9 (delta 0), reused 3 (delta 0), pack-reused 0 (from 0)
Receiving objects: 100% (9/9), done.

vitor@V▒tor MINGW64 ~
$ cd Avalia-o-github

vitor@V▒tor MINGW64 ~/Avalia-o-github (main)
$ git clone git@github.com:lucas-ryuichi/Avalia-o-github.git
Cloning into 'Avalia-o-github'...
remote: Enumerating objects: 12, done.
remote: Counting objects: 100% (12/12), done.
remote: Compressing objects: 100% (10/10), done.
Receiving objects: 100% (12/12), done.
Resolving deltas: 100% (1/1), done.
remote: Total 12 (delta 1), reused 5 (delta 0), pack-reused 0 (from 0)

vitor@V▒tor MINGW64 ~/Avalia-o-github (main)
$ cd Avalia-o-github

vitor@V▒tor MINGW64 ~/Avalia-o-github/Avalia-o-github (main)
$ git add .
warning: in the working copy of 'portugol.por', LF will be replaced by CRLF the next time Git touches it

vitor@V▒tor MINGW64 ~/Avalia-o-github/Avalia-o-github (main)
$ git commit -m "Terceira parte do código"
[main b63a7d6] Terceira parte do código
 1 file changed, 9 insertions(+), 3 deletions(-)

vitor@V▒tor MINGW64 ~/Avalia-o-github/Avalia-o-github (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 8 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 450 bytes | 450.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To github.com:lucas-ryuichi/Avalia-o-github.git
   570f31c..b63a7d6  main -> main

vitor@V▒tor MINGW64 ~/Avalia-o-github/Avalia-o-github (main)
$ ^C

vitor@V▒tor MINGW64 ~/Avalia-o-github/Avalia-o-github (main)
$ vitor@V▒tor MINGW64 ~
$ git pushcom:lucas-ryuichi/Avalia-o-github.git
