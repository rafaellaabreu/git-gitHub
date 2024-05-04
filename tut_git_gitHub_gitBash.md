# 📝 Tutorial Git e GitHub pelo Git Bash:

Abrir o git Bash

* Criar perfil no Git:

1. $ git --version     (versão do git)
2. $ git config --list (listar as configurações do Git)
3. $ git config --global user.name 'nome_usuario'
4. $ git config --global user.email 'email_usuario'

* Limpar o perfil do Git:

1. $ git config --global --unset user.name
2. $ git config --global --unset user.email
3. $ gitconfig --list

* Criar repositório no Git:

1. $ mkdir nome_pasta (criar uma pasta, caso não exista)
2. $ cd nome_pasta (acessar pasta)
3. $ ls (lista os arquivos da pasta)
4. $ git init (inicia o repositório)

* Subir o projeto do Git para o GitHub:

1. $ git status (monitora o status dos arquivos)
2. $ git branch -m main (garantir compatibilidade)
3. $ git add nome_arquivo (adiciona arquivo ou pasta específica)
4. $ git add . ( adicona todos os arquivos modificados)
5. $ git commit -m 'mensagem' (descrever sobre a modificação)
6. $ git remote add origin link_repositório (colar o link do repositório)
7. $ git push -u origin main (envia as alterações para o gitHub)

* Criar um repositório no GitHub:

1. repositório news
2. clicar em news
3. nome do repositório (o mesmo que o repositório local, se existir)
4. digitar descrição
5. escolher público ou privado
6. clicar em creater repository

* Clonar um repositório no gitHub para o Git:

1. página do repositório
2. clicar em <>code
3. copiar url do projeto
4. abrir o git bash
5. ir para a pasta escolhida
6. $ git clone url_copiada
7. $ git remote -v (lista do repositório remoto)

* Desfazer alteração no repositório local:

1. $ git init
2. $ rm -rf .git
3. $ git restore nome_arquivo

* Alterar a mensagem so último commit:

1. $ git commit --amend -m 'mensagem'

* Desfazer o último commit:

2. $ git reset --soft numero_commit
3. $ git reset --mixed numero_commit
4. $ git reset --hard numero_commit

* Histórico do git:
 
 1. $ git reflog

* Enviar e baixar alterações do repositório remoto:

1. $ git pull

