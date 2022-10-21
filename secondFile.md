# Revisão GIT WORKFLOW (básico)

> Basicamente a maior parte do trabalho com o git consiste nessas tarefas:
-> Editar
-> Commitar
-> Sincronizar com  repositório remoto

## Git Push
-> Enviar alterações (commits) de uma branch para o repositório remoto.
-> A primeira vez:
```
git push -u origin master
```
-> O envio é rejeitado se o repositório local não estiver sincronizado.
```
git push <remote> <branch>
git push
```

## Git Add
-> Adiciona os arquivos novos e modificados para o próximos commit

```
git add <lista de arquivos>
git add .
```

## Git Commit
-> Registra o commit com todos os arquivos que usou "git add"

```
git commit [-m "Message"]
```

-> Se o parâmetro de mensagem não for passado abrirá um editor de texto para escrever a mensagem (mas isso é muito difícil usar)
```
git config --global core.editor vscode
```
_ comandos:_
- git status:
    A gente visualiza o status do repositório git, ver os arquivos que não estão adicionado ao commit, e que já foram
- git log
    Mostra os ultimos commits feitos
- git add
    Adicionar arquivos ao commit 
- git commit
    Criar o commit
- git push
    Vai enviar todos commit que não foram enviados pro repositório de origem (github)
---
# Status dos arquivos
Editando o arquivo criado anteriormente (firstFile)
Criar um novo arquivo e ver o status no repositório