# Comando git revert

**Autor:** @MatheusRRocha22

## O que é?

O comando git revert é utilizado quando
é feito um commit com falhas e você deseja
retornar o código da branch ao commit anterior.

## Como utilizar?

Abra o terminal dentro da pasta do projeto
e execute:

```bash
git log --oneline //para buscar o hash do commit que você deseja voltar
```

Após buscar o hash do commit execute:

```bash
git revert {hash do commit que deseja voltar}
```

## Dica para iniciantes

Caso ocorra algum erro de Merge, remova a parte que não deseja e execute:

```bash
git add .
```

E logo após execute:

```bash
git revert --continue
```
