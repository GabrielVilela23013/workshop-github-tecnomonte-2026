# git status

**Autor:** @GuilhermeMartinsRO

## O que é?
O comando git status mostra a situação atual do repositório.
Ele informa a branch em uso e apresenta arquivos modificados,
arquivos preparados para commit e arquivos ainda não rastreados pelo Git.

## Como utilizar?
Abra o terminal dentro da pasta do repositório e execute:

```bash
git status
```

Por exemplo, depois de editar e salvar um arquivo README.md,
o comando pode mostrar esse arquivo como modificado.

Após executar:

```bash
git add README.md
git status
```

o arquivo aparecerá entre as alterações preparadas para o próximo commit.

## Dica para iniciantes
Execute git status antes de fazer um commit para conferir quais
alterações estão preparadas. O comando apenas consulta o estado
do repositório: ele não modifica arquivos nem envia alterações ao GitHub.