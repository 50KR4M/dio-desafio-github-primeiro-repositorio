

# Aula 4 -  Ciclo de vida Git 



## Conteúdo da aula
Descreve os diferentes estados dos arquivos envolvidos em um evento.

Tracked: arquivos novos adicionados e localizados dentro do repositório local (git Add):

- _Unmodified_: arquivo _tracked_ no comitado do estado _staged_.
- _Modified_: arquivo modificado do estado _unmodified_.
- Staged: arquivo recém adicionado pelo "git add" do estado _modified_ ou _untracked_.  

Untracked: Novo arquivo a ser inserido no repositório; arquivo não rastreado pelo Git.

## Comandos descritos na aula

git status: ver status (_tracked_ e _untracked_)    
mover arquivo: mv arquivo ./pastadestino/  
adicionar pastas: git add  nome/  
git add *: move todos os _untracked_ para _staged_

## Observações

**![img](https://lh6.googleusercontent.com/3asEpgYJQnZNd2wL0AAmAoGqpqhtyY_7vL_DOBZ0iH-NysHYfKlmRBJmFCsNYXiV1rvL7ox6H4G12etzJrOWVg8jslKazWOXXmozcFttDqpbviSs-qBBFgpKpgKOeEenHQhbbGvZ)**

Fig.1: Ciclos de vida do Git

![img](https://lh4.googleusercontent.com/_C5zX913naQJQIZYMc7yYmtKWRZFYjIO3zk-QkdBCKv8SOd8JzXG2JDIo0fPiJ9Ygt5pkszPShW_BQpsP6t6JRKUH5urIcLcIGIoAzT3njJ6hl9tWMoE-sqT3grRieqtmlhhPMrv)

Fig. 2: Estados do arquivo no ciclo de vida
