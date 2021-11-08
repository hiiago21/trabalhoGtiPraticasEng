# Guia de uso do Git


## Download do Git

Inicialmente precisa ser baixado o GUI client do Git, se você usa Linux pode usar o comando:

```console
sudo yum install git-all
```

ou

```console
sudo apt-get install git-all
```

Se você usa Windows pode fazer o download nesse link: https://git-scm.com/download/win


## Como criar um repositório e comandos básicos
Abra o terminal, vá até a pasta que deseja criar um repositório, e use o comando para inicializar o repositório

```console
git init
```

Comando para clonar um repositório
```console
git clone <link-do-repositório>
```

Comando para ver estado do Git
```console
git status
```

Comando para adicionar arquivos ao Git
```console
git add <nome-do-arquivo>
```
ou para adicionar todos arquivos
```console
git add *
```

Comando para fazer um commit
```console
git commit -m '<mensagem do commit>'
```

Comando para ligar seu repositório local ao repositório remoto
```console
git remote add origin <link-do-repositório>
```

Comando para enviar suas alterações
```console
git push
```

Comando para baixar atualizações do repositório
```console
git pull
```

Comando para criar branche
```console
git checkout -b <nome-da-branch>
```

Comando para trocar de branch
```console
git checkout <nome-da-branch>
```

Comando para realizar um merge
```console
git checkout main
git merge <nome-da-branch>
```