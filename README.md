# SQL Lab V1

Laboratório simples para exercícios de SQL no navegador.

## Como funciona

- O banco SQLite é criado automaticamente no navegador.
- O aluno digita SQL.
- `Executar SQL` mostra o resultado da consulta.
- `Verificar resposta` compara o resultado obtido com o resultado esperado.
- A comparação é feita pelo resultado, e não pelo texto do comando SQL.

## Publicar no GitHub Pages

1. Crie um repositório no GitHub.
2. Coloque o `index.html` na raiz.
3. Ative GitHub Pages usando a branch principal.
4. Abra o endereço gerado.

A aplicação usa SQL.js para executar SQLite no navegador.

## Observação

Esta V1 usa o arquivo SQL.js hospedado por CDN. Para uma versão totalmente independente da internet, os arquivos `sql-wasm.js` e `sql-wasm.wasm` podem ser colocados em uma pasta `libs/`.
