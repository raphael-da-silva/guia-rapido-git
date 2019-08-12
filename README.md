# Guia rápido de comandos Git

Abaixo contém alguns comandos básicos para trabalhar com [git](https://git-scm.com/doc).

### Comandos rápidos

Reverter o último commit (os arquivos comitados voltam para a stage area):
```
git reset --soft HEAD~1
```

Adicionar todas as mudanças para a stage area (inclusive os arquivos removidos):
```
git add --all
```
```
git add .
```

Editar a mensagem do último commit:
```
git commit --amend
```

Forçando o salvamento de alterações em um repositório remoto (o parâmetro -f refere-se a force):
```
git push -f
```

Remover um branch:
```
git branch -d nome-da-branch
```

Trocar de branch:
```
git checkout nome-da-branch
```

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
