# Git 

## Configuração Pós Instalação 

Em "editar variáveis de ambiente" entre na pasta PATH e na última linha crie uma nova variável chamada: PATH TO PUTHON


## Fucionalidade
Comandos no git bash no vscode ou terminal do bash.

Passo 01: Criar um versionamento da pasta onde está todos os arquivos

    git init 


Passo 2: Adicionar nome da pasta que será salva no repositório git

    git add

Passo 3: Adicionar um comentário no log do arquivo adicionado

    git commit -m = ""

## Resolução de Problemas na Instalação

    # git config --global user.email "marlon.santana@live.com"
    # git config --global user.name "marlonassisdv"


# GitHub

## Autenticação do Código p/ GitHub

Protocolo SSH: 

    1. Settings
    2. SSH and GPG Keys
    3. connecting to github SSH keys
    4. verificar se há chave SSH existente

Abra o Git Bash e insira:

    ls -al ~/.ssh

para ver se as chaves SSH existentes estão presentes.

## Gerando uma nova chave

Navegue pelo github até o tópico 4 e clique em "Gerando uma nova chave SSH e adicionando-a ao agents SSH"

    comando se encontra na etapa 2 "ssh-keygen..."

insira o e-mail e clique em Enter duas vezes após executar o comando

Por fim, execute o seguinte comando: 

    cat /c/Users/marlon/.ssh/id_ed2545615.pub

O comando vai gerar uma chave, e essa chave precisa ser criada dentro do github 

    1. settings
    2. SSH and GPG Keys 
    3. clique em "New SSH key"


# Criando Repositório 

Crie um novo repositório no GitHub e faça os seguintes comando no bash para subir os arquivos do projeto 

    1. 
    git remote add origin git@github.com:marlonassisdv/NomeDoRepositorio

    2. 
    git push -u origin main# Documentacao-GitHub
