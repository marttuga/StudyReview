
## GIT

## GET STARTED

```git
**git --version**  # Verifica a versão do Git instalada

**git init**  # Inicializa um novo repositório Git no diretório atual

**git config user.name "test"**  # Configura o nome do usuário para commits neste repositório
```

## NEW FILES

```git
**git status**  # Mostra o status dos arquivos no repositório (modificados, não rastreados, etc.)

**git add index.html**  # Adiciona o arquivo index.html ao staging (preparando-o para o commit)

**git add -A**  # Adiciona todas as mudanças no diretório (novos arquivos, modificações e exclusões) ao staging
```

## COMMIT

```git
**git commit -m "first commit"**  # Faz um commit das mudanças no staging com a mensagem "first commit"

**git status --short**  # Mostra o status dos arquivos em um formato mais conciso (curto)
```

## HELP

```git
**git status --help ** # Mostra a ajuda e opções disponíveis para o comando git status

**git help --all ** # Mostra a ajuda para todos os comandos Git disponíveis
```

## BRANCH

```git
**git branch new-branch ** # Cria uma nova branch chamada new-branch

**git branch**  # Lista todas as branches locais

**git checkout new-branch**  # Muda para a branch new-branch

**git checkout -b other-branch**  # Cria e muda para a branch other-branch
```

## BRANCH MERGE

```git
**git merge other-branch ** # Faz merge das mudanças da branch other-branch na branch atual

**git branch -d other-branch ** # Deleta a branch other-branch após o merge
```

## REMOTE 

```git
**git remote add origin https://github.com/x/y.git**  # Adiciona um repositório remoto chamado origin com a URL especificada

**git fetch origin**  # Busca as mudanças do repositório remoto origin

**git merge origin/master ** # Faz merge das mudanças da branch master do remoto origin na branch atual

**git pull origin**  # Puxa (fetch) as mudanças do remoto origin e faz merge automaticamente

**git push origin  **# Envia as mudanças da branch atual para o repositório remoto origin

**git branch -a ** # Lista todas as branches, incluindo as remotas

**git branch -r ** # Lista todas as branches remotas
```

## CLONE

```git
**git clone https://abc.com/x/y.git**  # Clona o repositório na URL especificada para um novo diretório

**git clone https://abc.com/x/y.git newlife ** # Clona o repositório na URL especificada para uma pasta chamada newlife

**git remote rename origin upstream**  # Renomeia o remoto origin para upstream
```

## .GITIGNORE

```git
***.temp  **# Ignora todos os arquivos com a extensão .temp

**temp/ ** # Ignora a pasta temp

**temp?.log ** # Ignora arquivos temp?.log (por exemplo, temp1.log, tempA.log, etc.)

***.log  **# Ignora todos os arquivos com a extensão .log

**!main.log**  # Excetua o arquivo main.log (não o ignora)
```

## REMOTE ADD SSH

```git
**git remote add ssh-origin git@abc.com:x/y.git**  # Adiciona um repositório remoto via SSH com o nome ssh-origin

**git remote set-url origin git@abc.com:x/y.git  **# Altera a URL do remoto origin para a URL SSH especificada
```

## REVERT

```git
**git log --oneline  **# Mostra o log dos commits em formato de uma linha por commit

**git revert HEAD ** # Reverte o último commit (gera um novo commit que desfaz as mudanças do último)

**git revert HEAD --no-edit ** # Reverte o último commit sem abrir o editor para a mensagem de commit

**git revert HEAD~1 ** # Reverte o penúltimo commit (HEAD~1 se refere ao commit anterior ao HEAD)
```

## RESET

```git
**git reset abc1234  **# Reseta o estado do repositório para o commit com o hash abc1234 (as mudanças após esse commit são removidas do histórico, mas permanecem no diretório dev trabalho)
```

## AMEND

```git
**git commit --amend -m "Updated index"  # Altera a mensagem do último commit para "Updated index" e inclui quaisquer mudanças no staging
```
