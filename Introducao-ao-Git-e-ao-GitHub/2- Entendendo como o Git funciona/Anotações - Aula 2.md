

# Aula 2 -  **Comandos básicos e bom desempenho no terminal**  



## Conteúdo da aula
SHA1  
Objetos fundamentais  
Sistema distribuído  
Segurança  

##### SHA1  

É uma função de dispersão criptográfica que pega uma mensagem de 264bits e produz um resumo de mensagem de 160 bits

##### Objetos fundamentais

_blobs_: contém metadados, informa o tipo de objeto, tamanho da _string_, tamanho do arquivo, etc.
_trees_: armazenam chaves (sha1) de blobs.
_commits_ (uso/prática): faz uma ação usando os dados dos _blobs_ e trees.dados: tree,parentes, autor, mensagem, etc.

##### Sistema distribuído

Git e GitHub: permite trabalhar em um projeto cooperativo através de várias máquinas e de um servidor comum remoto. É possível, graças a um sistema de versionamento do repositório remoto.

##### Segurança

A segurança de acesso ao repositório é garantido por meio da chave SSH e token 

## Comandos descritos na aula

openssl sha1 arquivo.formato: cria arquivo com criptografado com sha1

Git commit -m "mensagem": faz ação com os dados adicionados e põe descrição da ação em uma mensagem.

## Observações

ND
