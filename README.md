# Lista de comandos do git

### Criar novo repositório

```
git init
```

### Vincular repositório local com um repositório remoto

```
git remote add origin git@github.com:leocomelli/curso-git.git
```

## Adicionar arquivo/diretório para envio (staged area)

### Adicionar um arquivo em específico

```
git add meu_arquivo.txt
```

### Adicionar um diretório em específico
```
git add meu_diretorio
```

### Adicionar todos os arquivos/diretórios
```
git add .
```

## Comitar arquivo/diretório

### Comitar informando mensagem
```
git commit -m "minha mensagem de commit"
```

## Enviar arquivos/diretórios para o repositório remoto

### O primeiro push de um repositório deve conter o nome do repositório remoto e o branch.
```
git push -u origin master
```

### Os demais pushes não precisam dessa informação
```
git push
```

## Atualizar repositório local de acordo com o repositório remoto

### Atualizar os arquivos no branch atual
```
git pull
```

### Buscar as alterações, mas não aplica-las no branch atual
```
git fetch
```
## Branches

### Criando um novo branch
```
git branch nome-da-branch
```

### Trocando para um branch existente
```
git checkout nome-da-branch
```

### Criar um novo branch e trocar
```
git checkout -b nome-da-branch
```

### Resolver merge entre os branches
```
git merge nome-da-branch
```

### Listar branches
```
git branch
```

### Criando branches no repositório remoto
```
git push origin nome-da-branch
```
