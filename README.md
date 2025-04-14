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
  
