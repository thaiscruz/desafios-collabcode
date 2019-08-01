## Alteração Mensagem Git

A principio eu coloquei no meu commit essa mensagem:
```
git commit -m "Markdown e Alteracoes"
```

Mas eu queria mudar para outra, então adicionar o comando `--amend`.
```
git commit --amend -m "Markdown VsCode e Alteracoes"
```

Se você já tiver mandado para o github, tem jeito ainda, mas é **arriscado**. 
Você utiliza ainda o comando anterior e também executa esse:

```
git push --force
```