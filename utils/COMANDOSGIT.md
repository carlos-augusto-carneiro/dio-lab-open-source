# Comandos do Git

Esta página fala sobre alguns comandos do Git.

😁 Você também pode contribuir!

## ⚙️ Configurando o Git

- Configurar seu e-mail
- `$ git config user.email [seu_email_aqui]`
- Configurar seu nome de usuário
- `$ git config user.name [seu_usuario_aqui]`

Se você quiser configurar o escopo de trabalho, use as tags abaixo.

- Escopo local
  - `$ git config --local user.email [seu_email_aqui]`
- Escopo global
  - `$ git config --global user.email [seu_email_aqui]`
- Escopo do sistema
  - `$ git config --system user.email [seu_email_aqui]`

## 📚 Comandos Básicos

### Criar um novo repositório
  - Criar um repositório local
    - `$ git init`
  - Clonar um repositório remoto
    - `$ git clone [url_origem_remota]`
  - Clonar apenas um ramo (branch) do repositório
    - `$ git clone -branch [nome_do_branch] [url_origem_remota]`
  - Clonar para um diretório específico
    - `$ git clone [url_origem_remota] [nome_do_diretorio]`
  
### Criar uma nova conexão com o repositório remoto
- Listar repositórios remotos
  - `$ git remote`
- Criar uma nova conexão com o repositório remoto no servidor
  - `$ git remote add [nome_remoto] [url_para_repositorio_remoto]`
- Remover uma conexão com o repositório remoto
  - `$ git remote rm [nome_remoto]`
- Renomear uma conexão remota
  - `$ git remote rename [nome_antigo_remoto] [nome_novo_remoto]`

### Criar um novo commit
- Incluir arquivos na área de preparação (stage)
  - `$ git add --all ou -a ou .`
- Criar um commit com mensagem
  - `$ git commit -m "sua mensagem aqui"`
- Combinar tudo em um único commit
  - `$ git commit -a -m "sua mensagem aqui"`
- Alterar a mensagem do commit
  - `$ git commit --amend -m "nova mensagem aqui"`



# Git's Commands

This page is about some commands from Git. 

😁 You also can contribute!

## ⚙️ Settings Up Git

- Configure your email 
-  `$ git config user.email [your_mail_here]`
- Configure your user name 
- `$ git config user.name [your_user_here]`
  
If you want to config your scope of work use the tags below.

- Local scope 
  - `$ git config --local user.email [your_mail_here]`
- Global scope 
  - `$ git config --global user.email [your_mail_here]`
- System scope 
  - `$ git config --system user.email [your_mail_here]`

## 📚 Basics Commands

### Create a new repository
  - Create a local repository
    - `$ git init`
  - Clone a remote repository
    - `$ git clone [url_remote_origin]`
  - Clone only brachys repository
    - `$ git clone -branch [branch_name] [url_remote_origin]`
  - Clone into a specific repository
    - `$ git clone [url_remote_origin] [dir_name]`
  
### Create a new connection with the remote repository
- List remote repositories
  - `$ git remote`
- Create a new connection to remote repository on server
  - `$ git remote add [remote_name] [url_to_remote]`
- Remove a connection to remote repository
  - `$ git remote rm [remote_name]`
- Rename a remote connection
  - `$ git remote rename [remote_old_name] [remote_new_name]`

### Create a new commit
- Include files in stage area
  - `$ git add --all or -a or .` 
- Create a commit with message
  - `$ git commit -m "your message here"`
- Combine all in one commit
  - `$ git commit -a -m "your message here"`
- Change the message to commit
  - `$git commit -amend "new message here"`
