# Esse arquivo é referente ao modulo a onde pesso para criar um novo arquivo no arquivo secondFile...

![git status](./gitStatus.png)
---
## Estados dos arquivos
-> Não monitorado (untracked)
    Quando a gente cria ele.
-> Modificado (modified)
    Adiciona ele, comita ele ja está no repositório. e edita ele fica modified.
-> Preparado (Staged)
    Quando a gente da o git add, ele vira um arquivo staged, o git tem uma area, que os arquivos estao esperando para ser comitados.
-> Consolidado (commited)
    Consolidado/comitado.
![Estado do arquivo](./estadoArquivo.png)
---
# Comando Diff

-> Exibir diferenças entre commits e branchs
```
git diff
```

-> Diferença no diretório
```
git diff [path]
```

-> Mostra o que foi alterado no último commit 
->> Ver diff no GitHub
```
git diff HEAD~1
```