# Comandos Terminal

- `vim .zshrc` (configurações do zsh)

- `--version` (verifica que x programa está instalado e sua versão)
```
nomeDoPrograma --version
```
---
- `cd` (navega entre pastas)

Exemplo para entrar em uma pasta
```
cd nomeDaPasta
```
Exemplo para sair de uma pasta
```
cd .. 
```

---

- `mkdir` (cria pastas)
```
mkdir nomeDaPasta
```
---
- `ls` (lista os arquivos dentro da pasta)
```
ls
```


# Comandos Git

- `git init` (começar a seguir as pastas e arquivos de um projeto). Esse comando serve para começar um rojeto com o Git. Chamamos a pasta do projeto de repositorio. Para usar ele é só entrar na pasta do seu projeto, dessa forma, por exemplo:
```
/mnt/c/pasta/arquivo
```
E executar assim:
```
git init
``` 
---
- `git status` (informa o estado do repositório)
Você receberá informações sobre arquivos e pastas novos, removidos ou alterados

---
 - `git add` (segue os arquivos ou pastas no momento atual)
Com o comando `git status` você fica sabendo as informações dos arquivos e etc e com o `git add` você guarda esse momento dos arquivos e pastas para em seguida realizar o commit

Se você quer guardar o momento de todos os arquivos e pastas só executar o comando abaixo?
```
git add .
```
Mas se você quer pegar arquivos específicos, você pode deixar o comando mais direto:
```
git add pasta/arquivo
```
---

- `git commit` (gravar alterações) Você guarda o momento do seu repositório e pode adicionar uma mensagem para melhor identificação
```
git commit -m "titulo"
```
Quando você fizer modificações nas suas pastas e arquivos você não precisa usar o commando `add` e depois o `commit`, tem uma maneira mais rápida, porém se você criar uma pasta ou arquivo e usar esse comando, **não vai rastrear**, porque ele só é válido para modificacoes:
```
git commit -am "titulo"
``` 
---
- `git log` (lista dos estados que guardamos `commit`) Com esse comando conseguimos ver todos os `commit`'s que já fizemos na vida do repositório.

Para melhorar a leitura do git log, tem o comando abaixo que coloca as informações em uma linha
```
git log --pretty=oneline
```
>Para sair de algum comando aperte `"q"`. 

- `git remote add origin` (fazer o link entre o arquivo da máquina para o github)
```
git remote add origin linkRepositorioGithub
```

