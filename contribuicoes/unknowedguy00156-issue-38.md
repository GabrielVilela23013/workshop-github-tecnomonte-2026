# Comando git log

**Autor:** @unknowedguy00156

## O que é?

O comando `git log` mostra o histórico de commits de um repositório.
Para cada commit, ele exibe o identificador (hash), o autor, a data e a
mensagem. Com ele é possível entender o que foi alterado no projeto, quando
e por quem.

## Como utilizar?

Abra o terminal dentro da pasta do projeto e execute:

```bash
git log
```

Para ver o histórico de forma resumida, com um commit por linha:

```bash
git log --oneline
```

## Exemplo prático

Depois de fazer alguns commits, o resultado de `git log --oneline` pode ser:

```
a1b2c3d Adiciona explicacao sobre git log
9f8e7d6 Atualiza README
4c5b6a7 Primeiro commit
```

O commit mais recente aparece no topo da lista.

## Dica para iniciantes

Se o histórico for grande e a tela ficar "presa", pressione `q` para sair.
Use `git log --oneline` para uma visão rápida, em vez da versão completa.
