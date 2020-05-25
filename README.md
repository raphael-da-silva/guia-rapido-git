# Guia rápido de comandos Git

Abaixo contém alguns comandos básicos para trabalhar com [git](https://git-scm.com/doc).

### Registro de alterações (add, commit e etc)

Adicionar todas as mudanças para a stage area (inclusive os arquivos removidos):
```
git add --all
```

ou:
```
git add .
```

Editar a mensagem do último commit:
```
git commit --amend
```

Enviando os commits para o repositório principal:
```
git push
```

Forçando o salvamento de alterações em um repositório remoto (o parâmetro -f refere-se a force):
```
git push -f
```

### Branch

Trocar de branch:
```
git checkout nome-da-branch
```

Dar merge em uma brach na master
```
git checkout master
git merge nome-da-branch
```

Remover uma branch:
```
git branch -d nome-da-branch
```

### Stage area

Remover o arquivo do controle de versão:
```
git rm --cached nome-do-arquivo
```

Remover todos os arquivos da stage area:
```
git reset HEAD .
```

Descartar as mudanças em todos os arquivos modificados:
```
git checkout .
```

### Tags

Criar uma tag:
```
git tag nome-da-tag
```

Listar as tags do repositório:
```
git tag
```

Remover uma tag:
```
git tag -d nome-da-tag (o parâmetro -d refere-se a delete)
```

### Extra

Reverter o último commit (os arquivos comitados voltam para a stage area):
```
git reset --soft HEAD~1
```
